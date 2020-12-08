pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                docker {
                    image 'python:3' 
                }
            steps {
                echo 'Hello Jay the problem is not in steps'
            }
        }
    }
}
