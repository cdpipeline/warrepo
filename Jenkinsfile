pipeline {
    agent any 
    stages {
        stage('checkout') { 
            steps {
            git '' 
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn clean package' 
            }
        }
        }
        }
