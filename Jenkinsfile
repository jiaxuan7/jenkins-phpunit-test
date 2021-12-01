pipeline {
	agent {
		docker {
			image 'composer:latest'
		}
	}
	stages {
		
		stage('Test') {
			steps {
                sh '/usr/bin/phpunit tests'
            }
		}
	}
}
