pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'sh "/opt/maven -B -DskipTests clean install"'
      }
    }

  }
}