pipeline {
  agent any
  stages {
    stage('EMAIL') {
      steps {
        mail(subject: 'Successful Jenkins Job', body: 'This job is successful', from: 'oneilgpinto@gmail.com', to: 'oneilgpinto@gmail.com')
      }
    }
  }
}