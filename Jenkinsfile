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
	    stage('Compile'){
		    steps{
			    bat "mvn comile"
		    }}
    }
}
