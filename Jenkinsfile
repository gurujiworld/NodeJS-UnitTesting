@Library ('MY-SHared-Library') _
pipeline {
agent any
  stages {
    stage('build'){
      steps{
        script{
          build()
        }
      }
      
    }
    stage('deploy'){
      steps{
        script{
          deployDemo()
        }
      }
    } 
  }
}
