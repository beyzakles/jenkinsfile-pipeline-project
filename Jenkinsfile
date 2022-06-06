pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'HELLO V4'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }
        stage('run') {
            steps {
                echo 'HELLO V5'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}