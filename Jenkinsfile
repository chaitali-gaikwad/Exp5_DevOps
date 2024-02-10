pipeline {
    agent any
	tools {
		Recent node
	}
	stages {
        stage('Build') { 
            steps {
                sh 'npm version' 
            }
        }
    }
}
