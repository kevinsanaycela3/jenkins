pipeline {
  agent any
   stages {
    stage ('Build') {
      steps {    
        sh 'echo "HELLO kevin"'
        sh '''
        echo "welcome to B2"
        uname -a
        '''
     }
   }
    stage ('test') {
      steps {
        sh 'echo "HELLO sanaycela"'
        sh '''
        echo "This is testing"
        pwd
        ''' 
      }
    }
  }
}
