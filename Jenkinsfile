pipeline {
    options {
     buildDiscarder(logRotator(numToKeepStr: '3'))
    } 
    agent any
    
	stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    } 
}