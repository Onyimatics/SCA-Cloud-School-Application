pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git(url: 'git@github.com:Onyimatics/SCA-Cloud-School-Application.git', branch: 'master', credentialsId: '6107ee0e-a3ef-4347-a966-8fc16ce205d9')
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