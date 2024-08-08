pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/neoPerera/test-jenkis.git'
            }
        }
        stage('Build') {
            steps {
                // Add your build steps here
                sh 'echo "Building..."'
            }
        }
        stage('Test') {
            steps {
                // Add your test steps here
                sh 'echo "Testing..."'
            }
        }
        stage('Deploy') {
            steps {
                // Add your deploy steps here
                sh 'echo "Deploying..."'
            }
        }
    }
}
