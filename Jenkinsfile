pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
				git "https://github.com/bindujoshitha/medicare.git"
            }         
            }
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
	    Stage('Compile'){
		    steps{
			    bat "mvn comile"
		    }}
    }
}
