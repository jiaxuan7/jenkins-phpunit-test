pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Hello'
            }
        }
        stage('Test') {
            steps {
                sh '/usr/bin/phpunit tests'
            }
        }
    }
}
