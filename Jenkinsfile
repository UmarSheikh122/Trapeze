pipeline {
  agent any
  stages {
    stage('Git-Checkout') {
      steps {
        cleanWs(deleteDirs: true, notFailBuild: true, skipWhenFailed: true)
        echo 'Hello'
      }
    }

  }
}