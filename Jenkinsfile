pipeline {
  agent {
    docker {
      image 'nginx/nginx'
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
  }
}