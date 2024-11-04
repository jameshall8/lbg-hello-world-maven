pipeline {
  agent any
  tools {
    maven "m3"
  }

  stages {
     stage('Compile'){
      steps {
        sh 'mvn clean compile'
      }
  }
  }
 
}
