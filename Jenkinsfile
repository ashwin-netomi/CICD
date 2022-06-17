pipeline {
  agent any

  stages {
    stage('Test npm') {
      steps {
        sh """
          npm --version
          npm i
          npm run build
        """
      }
    }
  }
}