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
			        sh 'mvn -v'
				sh 'cat /etc/os-release'
			}
	}
    }
}
		        
			
