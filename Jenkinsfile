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
                sh 'mkdir -p deployment'
                sh 'cp app.py deployment/'
                sh 'ls deployment'
                sh 'echo Deployment Successful'
            }
        }
    }
}
