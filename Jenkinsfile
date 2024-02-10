pipeline {
	agent any
	tools {nodejs "LastestNode"}
	stages {
		stage('Build') {
			steps {
				bat 'npm install'
			}
		}
	}
}