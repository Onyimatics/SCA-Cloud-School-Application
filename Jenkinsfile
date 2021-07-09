pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git(url: 'git@github.com:Onyimatics/SCA-Cloud-School-Application.git', branch: 'master', credentialsId: '17f08133-a1f4-49b7-9871-1d33804f1a8c')
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