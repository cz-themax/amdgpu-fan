pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mkdir foo'
                sh 'ls'
            }
        }
        stage('Test') {
            steps {
                sh 'ls'
            }
        }
        stage('Deploy') {
            steps {
                sh 'exit 1'
            }
        }
    }
}

