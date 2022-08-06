pipeline {
  agent any
  stages {
    stage('Run & command') {
      steps {
        sh '''ls
pwd
date
cal 1984'''
      }
    }

    stage('Environment variable') {
      steps {
        echo 'hello world'
        echo 'BUILD_ID'
        sleep 5
      }
    }

    stage('Deploy on test') {
      steps {
        echo 'everything possible'
      }
    }

    stage('Deploy prod') {
      steps {
        echo 'this is write'
      }
    }

  }
}