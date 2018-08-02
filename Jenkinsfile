pipeline {
  agent {
    docker {
      image 'maven'
    }

  }
  stages {
    stage('Test') {
      steps {
        sshCommand(failOnError: true, command: 'ls -lrt')
      }
    }
  }
}