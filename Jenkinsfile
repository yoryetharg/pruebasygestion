pipeline {
  agent any
  stages {
    stage('QA') {
      steps {
        build(job: 'JOB2- MAVEN', propagate: true)
      }
    }

  }
}