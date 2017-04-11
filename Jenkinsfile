pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'Website'
      }
    }
    stage('Print') {
      steps {
        echo 'LOL'
      }
    }
    stage('Send') {
      steps {
        mail(subject: 'Done', body: 'This is done new build #', from: 'jenkins@sv.local', to: 'enzo@enzomignogna.onmicrosoft.com')
      }
    }
  }
}