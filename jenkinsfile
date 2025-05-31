pipeline{
	agent any
	tools{
		maven 'maven'
	}
	stages{
		stage('Checkout'){
			steps{
				git 'https://github.com/PrarthanaAshwath/MavenWeb.git'
			}
		}
		stage('Build'){
			steps{
				sh 'mvn clean package'			
			}
		}
		stage('Test'){
			steps{
				sh 'mvn clean package'			
			}
		}
		
	}
	
}
