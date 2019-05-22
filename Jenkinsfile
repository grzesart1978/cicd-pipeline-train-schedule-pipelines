pipline {
  agnet any
  stages {
    stage ('Build') {
     steps {
      echo 'Running buld automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
       }
     }
   }
}
