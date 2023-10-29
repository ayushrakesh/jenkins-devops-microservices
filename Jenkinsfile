
// SCRIPTED PIPELINE


// DECLARATIVE PIPELINE

pipeline {
	agent any
	stages{

stage('Build') {
	steps{
		echo "Build"

	}
	}
	stage('Unit Test') {
		
		steps{
		echo "Unit-Test"

		}
	}
	stage('Integration test'){
	
	steps{
		echo "Intregation-Test"

	}
	}
	}

	post{
always{
		echo "Always run"
	}
	success{
		echo "Success run"
	}
	failure{
		echo "Failure run"
	}
	}
	
	
}
