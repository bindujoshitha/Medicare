pipeline {
    agent any

    stages {
        
        stage( 'Build') {
            steps {
		    
          bat "mvn clean"
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
