pipeline {
    agent any
	tools {
		LastestNode 'LastestNode'
	}
	stages {
        stage('Build') { 
            steps {
                sh 'npm version' 
            }
        }
    }
}
