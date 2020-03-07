pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Good morning'
		}
	}
	    stage('two') {
		    parallel {
			    stage('test')
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
}
    

	

		        
			
