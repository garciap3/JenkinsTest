pipeline {
  agent { docker { image 'maven:3.3.3' } }
  stages {
    stage('build code') {
      steps {
        sh 'mvn --version' 
       }
    }
  }
}
