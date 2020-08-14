pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        build(job: 'NewJOb', propagate: true)
      }
    }

  }
}