pipeline {
    agent any 
    stages {
        stage('checkout') { 
            steps {
            git 'https://github.com/cdpipeline/warrepo.git'
            }
        }
        stage('Build') { 
            steps {
                sh 'git ls-files -u' 
            }
        }
        }
        }
