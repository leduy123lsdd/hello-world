pipeline {
      agent any

      stages {
            stage("Build") {
                  steps {
                        echo 'hello world'
                        sh 'cat Jenkinsfile'
                  }
            }

            stage("Test") {
                  steps {
                        echo 'hello world test'
                  }
            }

            stage("Deploy") {
                  steps {
                        echo 'hello world deploy'
                  }
            }
      }
}