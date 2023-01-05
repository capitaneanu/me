pipeline {
  agent any
  stages {
    stage('input') {
      steps {
        echo 'input step'
      }
    }

    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            echo 'test1 step'
          }
        }

        stage('') {
          steps {
            echo 'test 1.2'
          }
        }

      }
    }

    stage('test2') {
      steps {
        echo 'test2 step'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy step'
      }
    }

  }
}