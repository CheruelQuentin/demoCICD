pipeline {
  agent any
  stages {
    stage('mvn version ') {
      steps {
        sh 'mvn --version'
      }
    }

    stage('mvn package') {
      steps {
        sh 'mvn package'
      }
    }

    stage('mvn test') {
      steps {
        sh 'mvn test'
      }
    }

  }
}