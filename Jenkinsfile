pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'Hello1'
        echo 'Hello2'
      }
    }

    stage('stage2') {
      steps {
        echo 'Hello Stage 2'
        bat 'docker compose up'
      }
    }

  }
  environment {
    Demo = '2'
  }
}
