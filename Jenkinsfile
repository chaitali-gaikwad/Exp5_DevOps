pipeline {
    agent any
	tools {
		RecentNode '20.11.0'
	}
	stages {
        stage('Build') { 
            steps {
                sh 'npm version' 
            }
        }
    }
}
