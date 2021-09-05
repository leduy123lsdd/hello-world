pipeline {
      agent any

      stages {
            stage("Build") {
                  steps {
			sh 'sudo rm -f /home/leduy/pipline/hello-world && echo 123456'
			sh 'cp . /home/leduy/pipepline/hello-world'
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
