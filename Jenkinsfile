pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/priyaaxj/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Build Successful'
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
