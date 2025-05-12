
pipeline {
  /*agent any/slave1/dockeragent/k8s */
  agent any
  parameters {
    choice choices: ['dev', 'sit', 'prod', 'pt'], description: 'My environment ', name: 'ENV'
  }
  environment {
    JAVA_HOME = "/usr/bin/java"
  }

  stages {
    /*
    PR Pipeline 1. code checkout, 2. code build, 3. code quality,4. code vulnerabilty
    */
    stage('git checkout') {
      steps {
        script {
          println "Hello all welcome to pipelinescripting"
          var1=20
          println "myvar1 value is ${var1}"
          /* accessing variable of a parameters*/
          println "value of my selected environment is ${params.ENV}"
          /*accessing environment variables*/
          println "my java path is ${env.JAVA_HOME}"
          /*accessign default variables */
          println "my current workspace is ${WORKSPACE}"
        }
      }
    }
  }
}
