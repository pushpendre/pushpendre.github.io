pipeline {
  agent none
  stages {
    stage('1') {
      parallel {
        stage('1') {
          steps {
            echo '1'
          }
        }

        stage('1b') {
          steps {
            isUnix()
          }
        }

      }
    }

  }
}