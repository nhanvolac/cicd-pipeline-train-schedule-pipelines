pipelin {
  agent any
  stages {
    stage ('Build cai moi ne') {
      steps {
        echo 'Running build automation'
        sh './gradlow build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
