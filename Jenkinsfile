pipeline {
    agent { label 'backend' }
    stages {
        stage('build') {
            steps {
                sh "npm install"
                sh "npm run start"
            }
        }
    }
}