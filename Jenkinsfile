pipeline {
    agent { docker { image 'node:erbium-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}