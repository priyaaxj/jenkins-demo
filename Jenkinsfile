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
                sh 'mkdir -p deploy'
                sh 'cp app.py deploy/'
                sh 'echo Deployment Successful'
            }
        }
    }
}
