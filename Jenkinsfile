pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                mkdir -p deploy
                cp index.html deploy/
                '''
                echo 'Application deployed'
            }
        }
    }
}
