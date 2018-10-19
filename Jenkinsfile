pipeline {

  agent any

  stages {

    stage('checkout') {
      steps {
        git 'https://github.com/fdiotalevi/ta4j.git'
      }
    }
    
    stage('build') {
      steps {
        sh './mvnw clean package'
      }
      
    }

  }

}
