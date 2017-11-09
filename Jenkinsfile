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
  }
}