pipeline {
      agent any

      stages {
            stage("Build") {
                  steps {
			sh 'cp -r . /home/leduy/pipepline/hello-world'
                        sh './home/leduy/pipepline/build/mvn.sh'
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
