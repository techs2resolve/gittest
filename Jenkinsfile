pipeline {
  agent {
    node {
      label 'jenkins-slave'
    }

  }
  stages {
    stage('First Stage') {
      steps {
        writeFile(file: 'test123', text: 'test123')
      }
    }

  }
}