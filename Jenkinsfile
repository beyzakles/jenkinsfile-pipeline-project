pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Hello v3'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}