pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed ...'
        timeout(time: 5, unit: 'SECONDS') {
          sh 'sleep 10'
        }
      }
    }
    stage ('Test') {
      steps {
        echo "Test Completed ..."
      }
    }
    stage ('Deploy') {
      steps {
        echo "Deploy Completed ..."
      }
    }
  }
}