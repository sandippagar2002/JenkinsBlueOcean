pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hi Sandeep'
          }
        }

        stage('ParallelBuild') {
          steps {
            echo 'Build'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test'
      }
    }

  }
}