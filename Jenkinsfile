pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        echo 'Test'
      }
    }
    stage('Stage 2') {
      when {
        branch "master"
      }
      steps {
        echo 'This is master'
        sh 'ls -hal'
      }
    }
  }
}
