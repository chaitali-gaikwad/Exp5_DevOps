pipeline {
	agent any
	tools {nodejs "LastestNode"}
	stages {
		stage('Build') {
			steps {
				git 'https://github.com/chaitali-gaikwad/Exp5_DevOps'
				bat 'npm install'
			}
		}
	}
}