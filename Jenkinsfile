pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        echo 'Load code from Github'
        git(url: 'https://github.com/fullofdoubts/hello-world', branch: 'master', changelog: true, poll: true)
      }
    }

  }
}