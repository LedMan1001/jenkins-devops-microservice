pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build"
                echo "Test"
                echo "Integration" 
            }
        }
        stage('Test') {
	    steps {
	        echo "Test"
	    }
        }
        stage('Integration Test') {
	    steps {
	        echo "Integration" 
	    }
        }
    } 
    post {
        always {
            echo "always"
        }
        success {
	    echo "success"
        }
        failure {
	    echo "failure"
        }
      }
}
