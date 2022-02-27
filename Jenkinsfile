pipeline {
  agent any
  stages {
    stage('PRODUCCION') {
      steps {
        build(job: 'MAVEN-PROYECTO', propagate: true)
      }
    }

    stage('QA') {
      steps {
        build(job: 'JOB2-MAVEN', propagate: true)
      }
    }

  }
}