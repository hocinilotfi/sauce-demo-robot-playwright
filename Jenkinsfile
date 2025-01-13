Pipeline{
    agent{
        docker{
            image "ghcr.io/marketsquare/robotframework-browser/rfbrowser-stable:latest"
        }
    }
    stages{
        stage('afficher la version'){
            sh 'robot --version'
        }
    }
}