pipeline {
    agent any
	tools {
		RecentNode
	}
	stages {
        stage('Build') { 
            steps {
                sh 'npm version' 
            }
        }
    }
}
