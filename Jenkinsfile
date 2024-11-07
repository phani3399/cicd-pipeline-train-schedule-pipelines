pipeline{
  agents any
  stages{
    stage('build'){
      steps {
        echo 'running buold automatin'
        sh './gradlew build --no-daemom'
        archiveArtifacts aritfacts: 'dist/trainSchedule.zip'
          }
    }
  }
}
