pipeline {
    agent any
    
    tools{
        maven 'maven3'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        
        stage('compile') {
            steps {
               sh "mvn compile"
            }
        }
        
        stage('test') {
            steps {
                sh "mvn test"
            }
        }
        
        stage('package') {
            steps {
                sh "mvn package"
            }
        }
    }
}

