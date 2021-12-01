pipeline {
	agent any {
		docker {
			image 'composer:latest'
		}
	}
	stages {
		stage('Test') {
			steps {
                sh './vendor/bin/phpunit tests'
            }
		}
	}
}
