pipeline {
    agent { docker 'php' }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
        stage('run') {
            steps {
                sh 'php --version'
            }
        }
        stage('result') {
            steps {
                sh 'echo hello'
            }
        }
    }
}
