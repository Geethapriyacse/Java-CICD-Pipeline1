pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                bat 'javac Demo.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Demo'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying application to staging server...'
            }
        }

    }
}
