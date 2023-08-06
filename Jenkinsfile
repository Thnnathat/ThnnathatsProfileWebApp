pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Thnnathat/ThnnathatsProfileWebApp', branch: 'main')
      }
    }

    stage('Working Directory') {
      steps {
        sh 'pwd'
      }
    }

  }
}