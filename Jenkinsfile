pipeline {
  agent any 
  stages {
    stage('working with fileoperations') {
      steps {
        script {
          println "reading the content of file"
          File file = new File("/tmp/mydata.txt")
          println "my file content is ${file.readLines()}"
          for(line in file.readLines) {
            println "my line is ${line}"
          }
        }
      }
    }
  }
}
