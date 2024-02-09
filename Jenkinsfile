pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "Tarea3 PIPELINES"'
      }
    }
    stage('colocando en volumen el archivo') {
      steps {
        sh 'cp /var/jenkins_home/workspace/WEBapache_main/index.html /var/www/index.html'
      }
    }
  }
}
