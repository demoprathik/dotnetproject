pipeline {
  agent { label 'win-slave'}
  stages {
  stage('Build') {
  steps {
     bat 'dotnet clean'
     bat 'dotnet build --no-incremental'
}
}
}
}
