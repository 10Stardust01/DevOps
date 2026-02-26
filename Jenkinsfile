pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // This is where you run your file
                sh 'python3 p1.py'
            }
        }
    }
}
