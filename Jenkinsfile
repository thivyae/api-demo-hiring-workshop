pipeline {
  agent any
  stages {
    stage('BuildApp') {
      steps {
        git 'https://github.com/thivyae/BootcampAPITests.git'
      }
    }

    stage('Run Unit Tests') {
      steps {
        bat 'mvn clean install'
      }
    }

  }
}