pipeline {
  agent {
    node {
      label 'docker-agent-python'
    }
  }
  stages {
    stage('Create Zip File') {
      steps {
        echo "Create Zip File"
        sh '''
        echo "doing the Zipping.."
        '''
      }
    }
    stage('Update Lambda Function') {
      steps {
        echo "Update Lambda Function"
        sh '''
        echo "Updating Lambda Function.."
        '''
      }
    }
    stage('Upload to S3') {
      steps {
        echo "Upload to S3"
        sh '''
        echo "Uploading to S3"
        '''
      }
    }
    stage('Clean Up Workspace') {
      steps {
        echo "Clean Up Workspace"
        sh '''
        echo "Cleaned"
        '''
      }
    }
  }
}
