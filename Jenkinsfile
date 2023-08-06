pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Thnnathat/ThnnathatsProfileWebApp', branch: 'main')
      }
    }

    stage('Powershell') {
      steps {
        pwsh(script: 'pwd', encoding: 'utf-8', label: 'pwd')
      }
    }

  }
}