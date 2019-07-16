#!groovy
pipeline {

  libraries {
    lib 'TestLib'
  }
  
  agent any
  
  stages {
    stage ('Build') {
      steps {
        sh 'echo "Testing Shared Libraries"'
      }
    }
  }
}
