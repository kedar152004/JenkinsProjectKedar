pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                bat 'javac Hello.java'
                bat 'java Hello'
            }
        }
    }
}
