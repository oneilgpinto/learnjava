pipeline {
  agent any
  stages {
    stage('BUILD') {
      steps {
        mail(subject: 'Successful Jenkins Job', body: 'This job is successful', from: 'oneilgpinto@gmail.com', to: 'oneilgpinto@gmail.com')
        httpRequest(url: 'https://worldcup.sfg.io/matches/today', httpMode: 'GET', outputFile: 'F1.txt')
      }
    }
  }
}