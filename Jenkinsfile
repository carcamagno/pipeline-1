pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'python3 main.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}