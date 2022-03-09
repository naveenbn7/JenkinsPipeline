pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build is completed'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing is done'
          }
        }

      }
    }

    stage('Deployment') {
      steps {
        echo 'Code deployed to QA env'
      }
    }

  }
}