pipeline {
    agent any
    stages {
        stage('Check Python Version') {
            steps {
                // Check Python version
                sh 'python3 --version'
            }
        }
        stage('Hello') {
            steps {
                // Use 'python' command to run the script
                sh 'python3 hello.py'
            }
        }
    }
}


