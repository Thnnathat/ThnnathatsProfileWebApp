pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Thnnathat/ThnnathatsProfileWebApp', branch: 'main')
      }
    }

    stage('Powershell') {
      parallel {
        stage('Powershell') {
          steps {
            pwsh 'pwd'
          }
        }

        stage('Powershell 2') {
          steps {
            powershell 'pwd'
          }
        }

      }
    }

  }
}