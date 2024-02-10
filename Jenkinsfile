pipeline {
    agent any
	tools {
		nodejs '20.11.0'
	}
	stages {
        stage('Build') { 
            steps {
                sh 'npm version' 
            }
        }
    }
}
