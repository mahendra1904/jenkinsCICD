pipeline{
	agent any
	
	stages {	    
	    stage('gitclone') {

			steps {
				git branch: 'stag', credentialsId: 'githubid', url: 'https://github.com/mahendra1904/jenkinsCICD.git'
                
			}
		}
			
	}
	
}