pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                def a = new Log()
                a.nivel ="INFO" 
                a.tiempo = "sabado noche"
                a.texto = "mensaje de traza bala baalddlassdalsdal"
                a.enviarLog()
                def ruta = "/tmp/aaaa.txt"
                a.escribirLog(ruta)
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
