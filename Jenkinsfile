pipeline {
  agent any
  stages {
    stage('PDN') {
      steps {
        build(job: 'MAVEN-PROYECTO', propagate: true)
      }
    }

    stage('TOMCAT PDN') {
      steps {
        build(job: 'TOMCAT-MAVEN-MAIN', wait: true)
      }
    }

  }
}