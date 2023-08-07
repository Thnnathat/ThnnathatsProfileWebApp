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
        pwsh 'echo "Hello World"'
      }
    }

    stage('Hello Docker') {
      steps {
        pwsh 'docker run hello-world'
      }
    }

  }
}