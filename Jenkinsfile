pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'enter'
      }
    }

    stage('test_unit') {
      parallel {
        stage('test_unit') {
          steps {
            echo 'ok '
          }
        }

        stage('integration test') {
          steps {
            echo 'test integration '
          }
        }

        stage('code ') {
          steps {
            echo 'code '
          }
        }

      }
    }

    stage('src ') {
      steps {
        echo 'srcmsg'
      }
    }

  }
}