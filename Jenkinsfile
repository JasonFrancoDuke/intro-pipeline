library 'SharedLibs'
pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World!'
        sh 'java -version'
      }
    }
    stage('Shared Lib') {
       steps {
           helloWorld("Jenkins")
       }
    }    
  }
}
