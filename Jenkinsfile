pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'Node 14.x') {
                    npm install
                }
            }

        }
        stage('Deploy') {
            steps {
                nodejs(nodeJSInstallationName: 'Node 14.x') {
                    serverless deploy
                }
            }
        }
    }
}