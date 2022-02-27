pipeline {
  agent any
  stages {
    stage('PRODUCCIÓN') {
      steps {
        build(job: 'MAVEN-PROYECTO', propagate: true)
      }
    }

    stage('TOMCAT ') {
      steps {
        build(job: 'TOMCAT-MAVEN-MAIN', wait: true)
      }
    }

  }
}