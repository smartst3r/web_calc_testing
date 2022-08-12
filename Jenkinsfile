pipeline {

  agent any
  
  stages {
    
    stage("build") {
    
      steps {
        echo 'Building app'
        sh 'npm install'
        sh 'npm build'
      }
    
    }
    
    stage("test") {
    
      steps {
        echo 'Testing app'
      }
    
    }
    
    stage("deploy") {
    
      steps {
        echo 'Deploying app'
      }
    
    }
    
  }
}
