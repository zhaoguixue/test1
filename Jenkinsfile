pipeline {
  agent any
  stages {
    stage('bz1') {
      steps {
        sleep 5
      }
    }

    stage('bz2') {
      steps {
        build 'vdsv'
      }
    }

    stage('bz3') {
      steps {
        archiveArtifacts 'vgsdr'
      }
    }

  }
  environment {
    a = '1'
  }
}