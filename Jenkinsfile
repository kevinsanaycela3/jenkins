pipeline {
  agent any
   stages {
    stage ('Build') {
      steps {    
        sh 'echo "HELLO WORLD"'
        sh '''
        echo "This will list current dir content from latest"
        ls -lh
        '''
     }
   }
    stage ('test') {
      steps {
        sh 'echo "HELLO TEST"'
        sh '''
        echo "This lists the current directory"
        pwd
        ''' 
      }
    }
  }
}
