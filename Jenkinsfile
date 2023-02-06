pipeline{}
  agent any
  stages{
    stage ('Build'){
      echp 'Running build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}
