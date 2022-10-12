pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'Node js') {
                    sh 'echo Building'
                    sh 'npm run build'
                    sh 'open test'
                }
            }
        }
    }
}