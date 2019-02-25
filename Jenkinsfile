pipeline {
  agent any
  stages {
    stage('Cloning git') {
      steps {
        git(url: 'https://github.com/gustavoapolinario/node-todo-frontend', branch: 'master')
      }
    }
    stage('Install dependency') {
      steps {
        sh 'npm install'
      }
    }
    stage('Audit fix') {
      steps {
        sh 'npm audit fix'
      }
    }
  }
}