pipeline {
  agent any

  options {
    timestamps()
  }
  
  stages {
    
    stage('checkout') {
      steps {
        echo 'Checking out source code...'
        sh 'ls -la'
      }
    }

    stage('Build') {
      steps {
        echo 'Build stage...'
        sh 'echo "Simulating Build..."'
      }
    }

    stage('Test') {
      steps {
        echo 'Test stage'
        sh 'echo "Running tests..."'
      }
    }
  }

  post {
    success {
      echo 'Pipeline conpleted successfully'
    }
    failure {
      echo ' Pipeline failed'
    }
  }
}
        
    
    
