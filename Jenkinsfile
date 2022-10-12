pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo Building'
                sh 'npm run build'
                sh 'open test'
            }
        }
    }
}