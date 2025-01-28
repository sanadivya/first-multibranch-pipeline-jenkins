pipeline {
  agent any
  stages {
    stage('Master branch deploy code') {
      when{
        branch 'master'
      }
      steps {
        bat 'echo Building artifact from Master branch'
        bat 'echo Deploying code from Master branch'
      }
    }
    stage('Develop branch deploy code') {
      when{
        branch 'develop'
      }
      steps {
        bat 'echo Building artifact from develop branch'
        bat 'echo Deploying code from develop branch'
      }
    }
  }
}
