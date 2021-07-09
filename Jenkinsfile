pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git(url: 'git@github.com:Onyimatics/SCA-Cloud-School-Application.git', branch: 'master', credentialsId: 'a89e9736-e7c1-4e91-bddf-59303e257230')
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