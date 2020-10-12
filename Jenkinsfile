pipeline {
	agent { node { label 'ec2' } }
	options {
    		skipDefaultCheckout true
  	}
    stages {
        stage('build') {
            steps {
                sh 'pwd'
		sh 'cd /temp'
		sh 'git clone https://github.com/placid1/myApp-template.git'
            }
        }
    }
}
