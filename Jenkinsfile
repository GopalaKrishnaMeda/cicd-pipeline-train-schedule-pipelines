pipeline{
agent any
 stages{
    stage ("build"){
      steps{
             echo "build is running"
             sh "./gradlew build --no-dameon"
             ArchiveArtifacts artifacts: "dist/trainSchedule.zip"
    }
    }
    
}
}
