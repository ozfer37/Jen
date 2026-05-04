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
                sh 'javac Jen.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Jen'
            }
        }
    }
}
