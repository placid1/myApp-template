pipeline {
    agent any
	options {
    		skipDefaultCheckout true
  	}
    stages {
        stage('build') {
            steps {
                sh 'pwd'
		sh 'echo $USER'
		sh '''
                    cd /home/placid/Desktop
			mkdir -p dejan
                '''
            }
        }
    }
}
