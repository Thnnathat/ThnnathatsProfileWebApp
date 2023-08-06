pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Thnnathat/ThnnathatsProfileWebApp', branch: 'main')
      }
    }

    stage('Hello World') {
      steps {
        powershell 'echo "Hello World"'
      }
    }

  }
}