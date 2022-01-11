pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'My python pipeline'
                sh 'python --version'
                sh 'chmod 777 app.py'
                sh 'python3 app.py'
            }
        }
    }
}