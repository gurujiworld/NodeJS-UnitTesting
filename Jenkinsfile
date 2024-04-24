@Library ('MY-SHared-Library') _
pipeline {
agent any
tools {nodejs "node"}
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
