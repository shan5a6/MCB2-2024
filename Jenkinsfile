def mysum(a,b){
  sum = a + b
  println "sum of a & b is ${sum}"
}

pipeline {
  agent any 
  stages {
    stage('working with functions') {
      steps {
        script {
          mysum(300,400)
        }
      }
    }
  }
}
