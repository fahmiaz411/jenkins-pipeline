pipeline {
  agent any
  triggers {
		pollSCM("* * * * *")
	}
  stages {
    stage('Hello') {
      steps {
        echo 'Hello Pipe'
      }
    }
  }
}
