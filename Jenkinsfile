pipeline {
    agent any

    stages {
        stage('Ejecutar Comando pwd') {
            steps {
                echo 'Hola, este es un ejemplo de pipeline con "pwd"'
                sh 'cp -r /var/jenkins_home/workspace/tarea2 /var/www/git/'
            }
        }
    }
}
