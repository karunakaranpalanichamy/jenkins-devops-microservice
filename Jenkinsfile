pipeline {
	agent {
		docker {
		   image 'maven:3.6.3'	
		}
	}
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration') {
			steps {
				echo "Integration Test"
			}
		}
		
	} 
	
	 post {
			always {
				echo "i am awesome"
			}
		}
}
