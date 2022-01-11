pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'My python pipeline'
                sh 'python --version'
                sh 'python app.py'
            }
        }
    }
}