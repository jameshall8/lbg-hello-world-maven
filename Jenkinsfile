pipeline {
  agent any
  tools {
    maven "m3"
  }

  stage('Compile'){
    steps {
      sh 'mvn clean compile'
    }
  }
}
