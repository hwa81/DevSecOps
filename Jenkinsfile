pipeline {
  agent any
  environment {
      
  }
	stages {
    stage('DEV') {
      steps {
	  echo "Building in DEV"
       
      }
    }
  }
  stages {
    stage('TEST') {
      steps {
	  echo "After building in DEV, testing in TEST"
       
      }
    }
  }

	stages {
    stage('PROD') {
      steps {
	  echo "if testing was ok, deploy in PROD"
       
      }
    }
  }
}
