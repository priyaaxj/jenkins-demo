pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'echo Build Successful'
            }
        }

        stage('Test') {
            steps {
                sh 'cat app.py'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker build -t jenkins-demo .'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deployment Successful'
            }
        }
    }
}
