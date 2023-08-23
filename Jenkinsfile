pipeline {
  agent any
  stages {
    stage('Fetch code') {
      steps {
        git branch: 'main', url: 'https://github.com/omarhd66/lab-kustomize.git',
      }
    }
stage('Build') {
      steps {
        sh ls
      }
    }
   
  }
}
