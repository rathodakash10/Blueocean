pipeline {
  agent any
  stages {
    stage('Install Apache') {
      steps {
        sh 'sudo apt install apache2 -y'
      }
    }

    stage('Fetch code') {
      steps {
        git(url: 'git@github.com:rathodakash10/Blueocean.git', branch: '/Devops')
      }
    }

  }
}