pipeline {
  agent any

  environment {
    DB_ENGINE = 'sqlite'
  }


  stages {
    stage('Build') {
      steps {
        bat 'set'
        echo 'Building'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }
  }
  post {
    success {
      echo 'Success!'
    }
  }
}
