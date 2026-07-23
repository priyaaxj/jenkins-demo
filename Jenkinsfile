pipeline {
    agent any

    stages {

        stage('Workspace Check') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo 'Build Started'
            }
        }

        stage('Test') {
            steps {
                echo 'Test Started'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy Started'
            }
        }
    }
}
