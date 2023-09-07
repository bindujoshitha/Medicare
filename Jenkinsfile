pipeline {
    agent any

    stages {
        
        stage( 'Build') {
            steps {
				bat "mvnw clean "
            }
			
			}
		stage('Test') {
		
		
            steps {
				bat "mvnw test"
            }
        }
	    stage('Compile'){
		    steps{
			    bat "mvn comile"
		    }}
    }
}
