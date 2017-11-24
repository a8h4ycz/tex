pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building..'
          }
        }
        stage('error') {
          environment {
            jj = '45'
          }
          steps {
            echo 'gfsdgdsf'
            sh 'pwd'
            sh 'env'
          }
        }
        stage('ijk') {
          steps {
            acceptGitLabMR(mergeCommitMessage: 'oo')
          }
        }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
    stage('fsfsd') {
      steps {
        sh '''ps
'''
      }
    }
  }
}