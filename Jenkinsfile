pipeline {
  agent {
    node {
      label 'none'
    }

  }
  stages {
    stage('build') {
      steps {
        sh '/usr/bin/mvn clean package install'
      }
    }
    stage('done') {
      steps {
        sh 'echo hehe'
      }
    }
  }
}