pipeline {
    agent { label 'backend' }
    stages {
        stage('build') {
            steps {
                sh "npm run start"
            }
        }
    }
}