pipeline {
    agent any
    tools {
        // Specify the name of the Python installation configured in Jenkins
        python 'python3'
    }
    stages {
        stage('Build') {
            steps {
                // Use 'python' command to run the script
                sh 'python hello.py'
            }
        }
    }
}

