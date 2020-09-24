pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build phase'
            }

        }
        stage('Deploy') {
            steps {
                sh 'serverless deploy'
            }
        }
    }
}