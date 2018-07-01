pipeline {
  agent any
  stages {
    stage('DEV BUILD') {
      steps {
        mail(subject: 'Successful Jenkins Job', body: 'This job is successful', from: 'oneilgpinto@gmail.com', to: 'oneilgpinto@gmail.com')
        httpRequest(url: 'https://worldcup.sfg.io/matches/today', httpMode: 'GET', outputFile: 'F1.txt')
      }
    }
    stage('DEV DEPLOY') {
      steps {
        echo 'Deploy'
      }
    }
    stage('DEV TEST') {
      steps {
        echo 'DEV TEST'
      }
    }
    stage('ST DEPLOY') {
      steps {
        echo 'ST DEPLOY'
      }
    }
    stage('ST TEST') {
      steps {
        echo 'ST TEST'
      }
    }
  }
}