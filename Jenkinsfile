pipeline{
	agent any
	stages{
		stage("Stage1"){
			steps{
			   sh 'whoami'
			   sh 'docker --version'
			   sh 'docker compose version'
			}
		}
	}
}
