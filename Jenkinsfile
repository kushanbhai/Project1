pipeline {
    agent any
    stages {
        stage('One') {
                agent {
			docker {
				image 'httpd:latest'
			        }
			steps  {
			        echo 'Hi, Good Morning, Have a nice day'
			        }
		        
			
