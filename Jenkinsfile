pipeline {
  agent any
    stages {
      stage ('checkout') {
        steps {
          echo 'code checkout'
        }
      }
      stage ('Test') {
        steps {
          echo 'code is testing'
        }
      }
      stage ('build stage') {
        steps {
          echo 'code is build'
        }
      }
      stage ('Deployment') {
        steps {
          python Hello.py
        }
      }
    }
}
