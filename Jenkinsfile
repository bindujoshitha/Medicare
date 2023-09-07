pipeline {
    agent any

    stages {
        
        stage( 'Build') {
            steps {
		    withMaven {
          sh "mvn clean verify"
        }
            }
	}
		stage('Test') {
		
		
            steps {
				bat "mvn test"
            }
        }
	    stage('Compile'){
		    steps{
			    bat "mvn comile"
		    }}
    }
}
