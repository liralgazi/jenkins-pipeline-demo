pipeline {
    agent any

    stages {
        stage('Create empty file') {
            steps {
                sh 'touch empty_file.txt'
            }
        }

        stage('Echo message') {
            steps {
                sh 'echo "Hello from Pipeline!"'
            }
        }
    }
}