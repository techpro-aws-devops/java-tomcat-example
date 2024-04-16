pipeline {
    agent any
    stages {
        stage('Build Application') {
             steps{
                build job: 'build-web-application'
            }
        }
        stage('Deploy Application'){
            steps{
                build job: 'Deploy-Application'
            }            
        
        
        }
    }
}
