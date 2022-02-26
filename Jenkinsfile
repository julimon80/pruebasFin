pipeline {
  agent any
  stages {
    stage('PIPELINE1') {
      steps {
        build(job: 'JOB1', propagate: true)
      }
    }

  }
}