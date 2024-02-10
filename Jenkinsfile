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
		
		stage('Deploy to IIS') {
			steps {
				bat 'copy public C:\\inetpub\\wwwroot\\ReactTimetableApp'
			}
		}
	}
}