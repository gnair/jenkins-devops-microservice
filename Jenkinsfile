pipeline {
	agent {
		docker {
			image "maven:3.6.3"
		}
	}
	stages {
		stage('Build') {
			steps {
				sh "mvn --version"
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
	}
}
