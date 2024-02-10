pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'LastestNode') {
                    sh 'npm -v'
                }
            }
        }
    }
}