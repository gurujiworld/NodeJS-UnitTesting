@Library ('MY-SHared-Library') _
pipeline {
agent any
  stages {
    stage('build'){
      steps{
        script {
          build.java()
        }
      }
      
    }
    stage('deploy'){
      steps {
        script {
         msbuild.call()
        }
      }
    } 
  }
}
