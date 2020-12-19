pipeline {
	agent any
	
	stages {
		stage ('Compile Stage') {
		
			steps {
				sh '''
			cd HelloWorld
			mvn clean install
		'''
			}
		}
	stage ('Testing Stage') {

            steps {
                echo 'testing the application'
            }
        }


        stage ('Deployment Stage') {
            steps {
                echo 'deploying the application'
            }
        }
	}
}
