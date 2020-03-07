pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi, this is Zulaikha from edureka'
			
                }
        }
	    stage('Integration test') {
                        agent {
                                docker {
                                        reuseNode false
					image 'ubuntu'
                                        }
			}
	    }
    }
}

		        
			
