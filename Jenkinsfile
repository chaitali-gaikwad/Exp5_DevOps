pipeline {
    agent any
	tools {
		nodejs 'v20.11.0'
	}
	stages {
        stage('Build') { 
            steps {
                sh 'npm version' 
            }
        }
    }
}
