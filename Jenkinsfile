pipeline {
  agent any
  stages {
    stage('DEV: Build Deploy') {
      steps {
        echo 'Starting DEV Build & Deployment'
      }
    }
    stage('DEV: Unit Test') {
      steps {
        echo 'Starting DEV Unit Test'
      }
    }
    stage('ST: Deploy') {
      steps {
        echo 'Starting ST Deployment'
      }
    }
    stage('ST: Regression Test') {
      steps {
        echo 'Starting ST Regression Test'
      }
    }
  }
}