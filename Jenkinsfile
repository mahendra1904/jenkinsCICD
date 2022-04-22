pipeline{
    agent{}
    stages{
        stage('print sms'){
            echo 'pipeline started'
        }
        stage('poll code from scm'){
            git credentialsId: 'githubid', url: 'https://github.com/mahendra1904/jenkinsCICD.git'
        }
        stage('print sms'){
            echo 'code taken from github'
        }
    }
}