pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello, world!'
            }
        }
		stage('hit an ipconfig'){
			steps{
				bat 'ipconfig'
			}
		}
    }
}