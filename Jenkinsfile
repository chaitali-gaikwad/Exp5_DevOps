pipeline {
    agent any

	stages {
        stage('build') {
            steps {
                echo "Hello World!"
            }
        }
		
		stage('npm installation') { 
            steps {
				script {
					nodejs('LastestNode'){
						npm -v
					}
				}
            }
        }
    }
}