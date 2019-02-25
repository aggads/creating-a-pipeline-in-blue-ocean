pipeline {
  agent any
  stages {
    stage('Cloning git') {
      steps {
        git(url: 'https://github.com/gustavoapolinario/node-todo-frontend', branch: 'master')
      }
    }
  }
}