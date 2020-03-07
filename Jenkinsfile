pipeline {
    stages {
        stage('One') {
                agent {
			docker {
				image 'httpd:latest'
			}
			steps {
				sh 'htppd -v'
				sh 'cat /etc/os-release'
			}
}
	}
    }
}
		        
			
