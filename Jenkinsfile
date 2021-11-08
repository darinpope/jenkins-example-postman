pipeline {
  agent any
  stages {
    stage('run collection') {
      steps {
        sh 'docker run -t postman/newman run -h'
        sh 'docker run -t postman/newman run ./postman_collection.json'
      }
    }
  }
}