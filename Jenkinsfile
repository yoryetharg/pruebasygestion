pipeline {
  agent any
  stages {
    stage('MAVEN') {
      steps {
        build(job: 'MAVEN-PROYECTO', propagate: true)
      }
    }

  }
}