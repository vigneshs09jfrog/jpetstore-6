pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''def mvnHome = tool name: \'maven\', type: \'maven\'
sh "${mvnHome}/bin/mvn -B -DskipTests clean install"'''
      }
    }

  }
}