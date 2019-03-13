pipeline {
    agent none
    stages {
        stage('Build') {
	agent any
            steps {
                bat 'mvn package'
            }
        }
	}
}
