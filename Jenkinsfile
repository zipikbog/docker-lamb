pipeline {
  agent ivan
  stages {
    stage('Hello') {
      steps {
        sh 'ansible-playbook -i hosts playbook.yml'
      }
    }
  }
}
