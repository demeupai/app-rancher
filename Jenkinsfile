pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('Build') {
      steps {
        git(url: 'onsole.aws.amazon.com/iam/home?#/roles', branch: 'main')
      }
    }

  }
}