pipeline {
	agent any
	tools {nodejs "LastestNode"}
	stages {
		stage('install npm packages') {
			steps {
				bat 'npm install'
			}
		}		
		stage('Build project') {
			steps {
				bat 'npm run build'
			}
		}
	}
}