pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi, this is Zulaikha from edureka'
		}
                        agent {
                                docker {
                                        image 'httpd:latest'
                                        }
				steps {
					sh 'httpd -v'
					sh 'cat /etc/os-release'
				}
			}
	    }
    }
}

		        
			
