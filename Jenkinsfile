pipeline {

agent node1

stages {
	stage("SCM") {
		steps{
			echo "pull the code from the github"	
			git 'https://github.com/Vikash911/maven-app.git'
		}

		}
	stage("Deploy") {
		steps {
			sh 'mvn clean package'
		}
		
		}
	stage("Test"){
		steps {
			sh 'java -jar target/*.jar'

		}
	}
	stage("deploy to Prod"){
		steps {
			echo "deploy the page to the production"
		}
	}

	}
}
