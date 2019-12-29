pipeline
    {
    agent any
    stages {
      stage ('Build') {
        steps {
          echo "Running Build for Train-Shedule APP"
          sh './gradlew build'
          archiveArtifacts artifacts: 'dist/TrainShedule.zip'
          }
       }
      }
}
