pipeline {
  agent any 
  stages {
    stage('working with loops') {
      steps {
        script {
          for(i=1;i<=5;i++) {
            println "my i value is ${i}"
          }
          lis1=["devops","aws","scripting"]
          for (ele in lis1) {
            println "my list element is ${ele}"
          }
          
        }
      }
    }
  }
}
