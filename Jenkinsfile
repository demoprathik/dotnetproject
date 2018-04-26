pipeline {
  agent { label 'win-slave'}
  stages {
  stage('Build') {
  steps {
     sh 'dotnet clean'
     sh 'dotnet build --no-incremental'
}
}
}
}
