pipeline{
	agent any
	
	stages {	    
	    stage('poll scm') {

            steps{
                echo 'hi i am here'
                # slack integration 
                slackSend baseUrl: 'https://hooks.slack.com/services/', channel: 'prod', color: 'red', iconEmoji: ':)', message: 'hi i am jenkins job', teamDomain: 'pmc-corp-ltd', tokenCredentialId: 'slack'

            }

			
		}
			
	}
	
}