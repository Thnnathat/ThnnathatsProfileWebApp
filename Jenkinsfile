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
        sh 'echo "Hello World"'
      }
    }

    stage('Hello Docker') {
      steps {
        sh 'docker run hello-world'
      }
    }

  }
}