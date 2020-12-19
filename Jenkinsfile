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
	}
}
