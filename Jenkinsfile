pipeline {
	agent any

	stages {
		stage('Build') {
			steps {
				sh 'mvn --version'
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('IntegrationTest') {
			steps {
				echo "IntegrationTest"
			}
		}
	} post  {
		always {
			echo "Completed"
		}
		success {
			echo "Success"
		}
		failure {
			echo "Failure"
		}
	}
}
