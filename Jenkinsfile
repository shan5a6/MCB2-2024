pipeline {
  agent any 
  stages {
    stage('working with conditions') {
      steps {
        script {
          a = 10
          b = 20
          if ( a > b) {
            println "value ${a} is big"
          }
          else {
            println "value ${b} is big"
          }
        }
      }
    }
  }
}
