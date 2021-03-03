pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'docker-compose build'
            }
        }
        stage('Push') {
            steps {
                sh 'docker push pipeline-1_app:latest'
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