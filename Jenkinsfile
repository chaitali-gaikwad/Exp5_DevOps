pipeline {
    agent any
	tools {
		nodejs 'LatestNode'
	}
	stages {
        stage('Build') { 
            steps {
                sh 'npm version' 
            }
        }
    }
}
