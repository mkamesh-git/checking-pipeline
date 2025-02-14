pipeline {
    agent none
    stages {
        stage('Build') {
            agent { label 'build-node' }
            steps {
                echo 'Building the application...'
            }
        }
        stage('Test') {
            agent { label 'test-node' }
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            agent { label 'deploy-node' }
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}

