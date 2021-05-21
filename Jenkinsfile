pipeline {
    agent any

    stages {
        stage('Check out') {
            steps {
                 git branch: 'main', credentialsId: 'GP', url: 'https://github.com/thegeneralpublic/GCP-Identify-ipv6.git'
                 sh 'ls'
                 sh 'git branch'
            }
            
        }
        stage('the end') {
            steps {
                echo 'Thanks'
                 
            }
            
        }
    }
}
