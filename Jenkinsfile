pipeline {
    agent any
    stages {
        stage('paralele') {
               parallel{
					stage('prima'){
						agent {
							label "any"
						}
						steps {
							bat "ipconfig"
						}
					
					}
					stage('a doua'){
						agent {
							label "any"
						}
						steps {
							bat "ping 127.0.0.1"
						}
					}
			   }
            
        }
    }
