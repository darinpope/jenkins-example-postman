pipeline {
  agent any
  stages {
    stage('run collection') {
      steps {
        sh 'docker run -t postman/newman run "https://www.getpostman.com/collections/0d0350a9a89d39fb6361"'
      }
    }
  }
}