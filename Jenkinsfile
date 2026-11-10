pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'echo Building Application'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 app.py'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deployment Successful'
            }
        }
    }
}
