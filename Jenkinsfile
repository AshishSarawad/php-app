pipeline {
  agent any
  stages {
      
    stage('verify version') {
      steps {
        withSonarQubeEnv(installationName: 'sonarqube', credentialsId: 'sonar') {
            
       }
        sh 'php --version'
      }
    }
    stage('hello') {
      steps {
        sh 'php hello.php'
      }
    }
  }
}