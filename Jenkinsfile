pipeline {
    agent { label 'backend' }
    options {
        timeout(time: 1, unit: 'MINUTES') 
    }
    stages {
        stage('build') {
            steps {
                sh "npm install"
                sh "npm run start"
            }
        }
    }
}