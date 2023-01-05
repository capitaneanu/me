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
        stage('test1.1') {
          steps {
            echo 'test1.1 step'
          }
        }

        stage('test1.2') {
          steps {
            echo 'test 1.2'
          }
        }

      }
    }

    stage('test2') {
      parallel {

        stage('test2.1') {
          steps {
            echo 'test 2.1'
          }
        }
        
        
        stage('test2.2') {
          steps {
            echo 'test 2.2'
          }
        }
        
        
        stage('test2.3') {
          steps {
            echo 'test 2.3'
          }
        }
        
        
        stage('test2.4') {
          steps {
            echo 'test 2.4'
          }
        }
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy step'
      }
    }

  }
}
