pipeline {
  agent any
  stages {
    stage('Get sources') {
      parallel {
        stage('Get sources') {
          steps {
            echo 'Get source code'
            echo 'Get binaries'
          }
        }
        stage('') {
          steps {
            echo 'Get sources'
          }
        }
        stage('Get binaries') {
          steps {
            echo 'Get binaires'
          }
        }
      }
    }
    stage('RHEL 6') {
      parallel {
        stage('RHEL 6') {
          steps {
            echo 'RHEL 6'
          }
        }
        stage('RHEL 8') {
          steps {
            echo 'RHEL 8'
          }
        }
        stage('Windows') {
          steps {
            echo 'Windows'
          }
        }
        stage('Fedora 29') {
          steps {
            echo 'Fedora 29'
          }
        }
        stage('Fedora 30') {
          steps {
            echo 'Fedora 30'
          }
        }
        stage('RHEL 7') {
          steps {
            echo 'RHEL 7'
          }
        }
      }
    }
  }
}