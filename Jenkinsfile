pipeline {

agent any

stages {
	stage("SCM") {
		steps{
			echo "pull the code from the github"	
		}

		}
	stage("Deploy") {
		steps {
			echo "deploy the web page"
		}
		
		}
	stage("Test"){
		steps {
			echo "testing the app"

		}
	}
	stage("deploy to Prod"){
		steps {
			echo "deploy the page to the production"
		}
	}

	}
}
