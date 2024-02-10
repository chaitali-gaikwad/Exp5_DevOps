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
				bat 'Xcopy build C:\\inetpub\\wwwroot\\ReactTimetableApp /E /H /C /I /Y'
			}
		}
	}
}