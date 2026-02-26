pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'python3 --version'
                // Add steps to install dependencies, e.g., sh 'pip install -r requirements.txt'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..." '
                // Run your tests, e.g., sh 'pytest'
            }
        }
    }
}

stage('Test') {
    steps {
        sh 'python3 p1.py' 
    }
}
