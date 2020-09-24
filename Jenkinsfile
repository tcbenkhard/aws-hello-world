pipeline {
    agent any

    stages {
        stage('Build') {
            echo 'Build phase'
        }
        stage('Deploy') {
            sh 'serverless deploy'
        }
    }
}