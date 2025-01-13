Pipeline{
    agent{
        docker{
            image "ghcr.io/marketsquare/robotframework-browser/rfbrowser-stable:latest"
            label 'my-defined-label'
            args  '-v /tmp:/tmp'
        }
    }
    stages{
        stage('afficher la version'){
            sh 'robot --version'
        }
    }
}