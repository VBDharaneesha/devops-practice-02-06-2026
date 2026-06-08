pipeline{
	agent any
	stages {
		stage ('cloning from scm') {
			steps {
				git branch: 'master',
				    credentialsId: 'git-demo',
				    url: 'https://github.com/VBDharaneesha/devops-practice-02-06-2026.git'
				}
				
			}	
		
		}

	}
