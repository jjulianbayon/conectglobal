pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -l' 
            }
        }
	stage ('Test'){
	    steps {
		echo 'Testing'
           }
	}
	stage ('Deploy'){
	   steps {
		echo 'Desplegando'
           }

	}
	
    }
}
