pipeline {
	agent {
		node {
			label 'ubuntu'
		}
	}
	options {
    		skipDefaultCheckout true
  	}
    stages {
        stage('build') {
            steps {
                sh 'pwd'
		sh 'git clone https://github.com/placid1/myApp-template.git'
            }
        }
    }
}
