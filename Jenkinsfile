pipeline {
  agent any
  stages {
    stage('Git CheckOut') {
      steps {
        git(url: 'https://github.com/k9nadav/BlueOcean_repo.git', branch: 'main')
        echo 'Successfully checked out from GitHub'
      }
    }

    stage('compile') {
      steps {
        sh 'bash comoile.sh'
      }
    }

  }
}