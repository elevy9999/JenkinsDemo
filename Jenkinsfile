pipeline {
      agent {
        docker { image 'node:14-alpine' }
    }
  stages {
    stage('build') {
      steps {
        sh 'echo "hello"'
      }
    }
   stage('Test') {
            steps {
                sh 'node --version'
            }
        }
      
  }
}
