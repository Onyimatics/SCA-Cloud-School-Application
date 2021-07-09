pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git(url: 'git@github.com:Onyimatics/SCA-Cloud-School-Application.git', branch: 'master')
      }
    }

    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}