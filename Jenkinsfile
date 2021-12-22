pipeline{
  
  agent any
  stages {
    stage ('Build') {
      steps {
        echo "this is my first build'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
  
}
