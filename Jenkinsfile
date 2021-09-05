pipeline {
      agent any

      stages {
            stage("Build") {
                  steps {
			sh 'pwd'
                  }
            }

            stage("Test") {
                  steps {
                        sh './home/leduy/pipepline/test/test.sh'
                  }
            }

            stage("Deploy") {
                  steps {
                        echo 'hello world deploy'
                  }
            }
      }
}
