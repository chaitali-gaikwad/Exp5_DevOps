pipeline {
    agent any
	tools {
		LatestNode 'LatestNode'
	}
	stages {
        stage('Build') { 
            steps {
                sh 'npm version' 
            }
        }
    }
}
