pipeline {
  agent { label 'linux' }
  stages {
    stage('Hello') {
      steps {
        sh 'ansible-playbook -i hosts playbook.yml'
      }
    }
  }
}
