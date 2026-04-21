pipeline {
    agent any
     tools {
        maven 'node'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}