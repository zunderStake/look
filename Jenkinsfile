pipeline {
  agent {
    docker {
      image 'node:12'
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