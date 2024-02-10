pipeline {
    agent any
	tools {
		nodejs 'LastestNode'
	}
	stages {
        stage('Build') { 
            steps {
                sh 'npm -version' 
            }
        }
    }
}
