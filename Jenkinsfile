pipeline {
  agent any
  stages {
    stage('one') {
      steps {
        sh '''lscpu
lsmem
'''
      }
    }

  }
  environment {
    dev = 'done'
  }
}