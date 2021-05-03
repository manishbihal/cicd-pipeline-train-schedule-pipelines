pipeline {
  agent any
  
  stages {
    stage('Build') {
      
      steps {
        echo 'running build automation'
        sh './gardelw build --no-deamon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
         }
      }
   }
}
