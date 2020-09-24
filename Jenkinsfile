pipeline {
    agent any

    stages {
        stage('Build') {
            scm checkout
        }
        stage('Deploy') {
            sh 'serverless deploy'
        }
    }
}