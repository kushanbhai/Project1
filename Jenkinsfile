pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi, this is Zulaikha from edureka'
			
                }
        }
	    stage('two') {
                        agent {
                                docker {
                                        image 'httpd:latest'
                                        }
			}
	    }
    }
}

		        
			
