pipeline {
  agent {
    node {
      label 'Vinod_slave_hyd08'
    }

  }
  stages {
    stage('chkout') {
      steps {
        sh 'git clone https://github.com/gkdba87/ansible'
      }
    }
  }
}