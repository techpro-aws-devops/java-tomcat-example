pipeline {
    agent any
    stages {
        stage('Build Application') {
             steps{
                build job: 'build-web-application'
            }
        }
        stage('Deploy to Staging Environment'){
            steps{
                build job: 'Deploy-Application-Staging-Environment'
            }            
        
        
        }
    }
}
