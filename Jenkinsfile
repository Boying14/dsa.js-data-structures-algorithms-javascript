pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        echo 'Hello'
        timestamps() {
          sleep(unit: 'MILLISECONDS', time: 10)
        }

      }
    }

    stage('deploy') {
      parallel {
        stage('deploy') {
          steps {
            echo 'deploy1'
          }
        }

        stage('') {
          steps {
            echo 'hihi'
          }
        }

      }
    }

  }
}