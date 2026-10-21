pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'node --version'
                sh 'npm --version'
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                sh 'node test.js'
            }
        }
    }
}