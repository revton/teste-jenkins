pipeline {
    agent any

    tools {
        python 'Python 3.9'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the application...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Testing the application...'
            }
        }
        stage('Docs') {
            steps {
                echo 'Deploying docs...'
            }
        }
    }
}