pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'git stage'
      }
    }

    stage('Deliver') {
      steps {
        sh 'git commit -m "Add \'Deliver\' stage"'
      }
    }

  }
}