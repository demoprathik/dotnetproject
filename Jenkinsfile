pipeline {
  agent { label 'win-slave'}
  stage('Build') {
  steps {
     bat 'dotnet clean'
     bat 'dotnet build --no-incremental'
}
}
}
