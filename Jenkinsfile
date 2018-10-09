pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/mixpix3ls/terraform-book', branch: 'master', changelog: true)
      }
    }
  }
}