pipeline {
    agent any
    stages {
        stage('One') {
                agent {
			docker {
				image 'maven:3-alpine'
			        }
		}
			steps  {
			        sh 'maven --version'
				sh 'cat /etc/os-release'
			}
	}
    }
}
		        
			
