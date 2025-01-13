pipeline {
    agent{
        docker{
            image "ghcr.io/marketsquare/robotframework-browser/rfbrowser-stable:latest"
            args '--entrypoint=""'
        }
    }
    stages{
        stage("stage 1"){
            steps{
                    sh 'echo "********* stage 1"' 
            }
            
        }
        stage('afficher la version'){
            steps{
                sh 'robot --version'
            }
        }
         stage("stage 3"){
            steps{
                sh 'echo "********* stage 3"' 
            }
            
        }

    }
}