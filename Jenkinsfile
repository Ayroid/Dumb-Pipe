pipeline{
  agent any
  pre {
    echo "Pipeline starting!"
  }
  stages {
    stage('STAGE 1 : BUILD'){
      steps{
        echo "Building the application..."
      }
    }
    stage('STAGE 2 : TEST'){
      steps{
        echo "Testing the application..."
      }
    }
    stage('STAGE 3 : DEPLOY'){
      steps{
        echo "Deploying the application..."
      }
    }
  }
  post {
    echo "Pipeline ran successfully!"
  }
}
