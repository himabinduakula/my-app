pipeline {
  agent any
  stages {
    stage('get code') {
      steps {
        git(url: 'https://github.com/himabinduakula/my-app.git', branch: 'master', changelog: true)
      }
    }

  }
}