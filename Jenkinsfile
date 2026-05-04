pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/ozfer37/Jen.git'
            }
        }

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
