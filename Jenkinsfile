pipeline {
  agent {
    docker {
      image 'nginx'
    }
    
  }
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
  }
}