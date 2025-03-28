pipeline {
    agent any
    stages {
        stage('Clone Code') {
            steps {
                git 'https://github.com/akash5022gupta/ci-cd-docker-k8s.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
