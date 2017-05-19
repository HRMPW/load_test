pipeline {
  agent any
  stages {
    stage("Load") {
      steps {
        load "loadtest.groovy"
        step([$class: 'LogParserPublisher', useProjectRule: false])
      }
    }
  }
}
