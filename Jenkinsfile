
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code fetched from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage started'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project files'
                sh 'test -f index.html'
                echo 'index.html exists'
            }
        }
    }
}
