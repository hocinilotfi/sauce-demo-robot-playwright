pipeline {
    agent{
        docker{
            image "ghcr.io/marketsquare/robotframework-browser/rfbrowser-stable:latest"
            args '--entrypoint=""'
        }
    }
    stages{
        stage('afficher la version'){
            steps{
                sh 'robot --version'
            }
            
        }
    }
}