pipeline {
  agent none
  stages {
    stage('lint') {
      steps {
        sh 'echo \'linting api\''
      }
    }
    stage('fast tests') {
      steps {
        sh 'echo \'running fasts tests\''
      }
    }
    stage('slow tests') {
      steps {
        sh 'echo \'running slow tests\''
      }
    }
    stage('selenium') {
      parallel {
        stage('selenium') {
          steps {
            sh 'echo \'running selenium\''
          }
        }
        stage('selenium chrome') {
          steps {
            sh 'echo \'running selenium chrome\''
          }
        }
      }
    }
  }
}