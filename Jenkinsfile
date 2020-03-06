pipeline {
    agent any
    stages {
        stage('One') {
                agent {
			docker {
				image 'httpd:latest'
			        }
		}
			steps  {
			        sh 'cat /etc/os-release'
			}
	}
    }
}
		        
			
