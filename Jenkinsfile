pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'echo "building"'
      }
    }
  }
  environment {
    test = 'test'
  }
}