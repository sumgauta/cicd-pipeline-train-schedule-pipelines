pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
         build steps
      }
    }
    stage('Test') {
      steps { 
         test steps  
      }
    }
    stage('Deploy') {
      steps {
         deploy steps
      }
    }
  }
}
