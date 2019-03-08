pipeline{
agent any
Stages {
   stage {'Build'} {
   steps {
    echo 'Running Build automation'
    sh  './gradlew  build --no-daemon'
    archiveArtifacts artifact: 'dist/trainSchedule.zip'
         }
      }
   }
}
