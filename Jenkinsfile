pipeline {
    agent any

	stages {
        stage('Build') { 
            steps {
				script {
					nodejs('LastestNode'){
					
						//here your npm commands p.e.
						npm -v
						//npm install
						
					}
				}
            }
        }
    }
}
