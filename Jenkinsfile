pipeline {
  agent {
    node {
      label 'linux'
    }

  }
  stages {
    stage('build') {
      agent {
        node {
          label 'linux'
        }

      }
      steps {
        sh 'echo build'
      }
    }

  }
}