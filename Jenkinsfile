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

        stage('Deploy') {
            steps {
                sh 'echo Deployment Successful'
            }
        }
    }
}
