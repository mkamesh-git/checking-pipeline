pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        stage('Test') {
           
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            
            steps {
                echo 'Deploying the application...'
            }
        }

        stage('create a file') {
            
            steps {

            sh 'echo "Hello, Jenkins!" > myfile.txt'  // Create a file
    }

}
        stage('create a file'){
            step{
                sh 'touch kamesh.sh'
            }
        }
    }
}
