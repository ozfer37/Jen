pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                bat 'javac Jen.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Jen'
            }
        }
    }
}
