pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'My python pipeline'
                sh 'python --version'
                sudo python3 app.py
            }
        }
    }
}