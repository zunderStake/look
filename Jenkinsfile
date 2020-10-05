pipeline {
  agent {
    docker {
      image 'node:12'
      args '--network mynet'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'cd ./example-react; npm install'
      }
    }

  }
}