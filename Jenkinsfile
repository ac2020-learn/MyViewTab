pipeline {
    agent any

    stages {
        stage('Setup') {
            steps {
                echo 'Hello World'
                bat 'atlas-version'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Hello World'
                bat 'atlas-compile'
            }
        }
        
        stage('Package') {
            steps {
                echo 'Hello World'
                bat 'atlas-package'
            }
        }        
 
         stage('Deploy') {
            steps {
                echo 'Hello World'
                bat 'set'
            }
        }
    }
}
