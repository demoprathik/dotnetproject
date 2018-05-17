pipeline {
  agent  {label 'winslave'}
  stages {
  stage('Build') {
  steps {
    script {
     bat 'dotnet clean'
     bat 'dotnet build --no-incremental'
}
}
}
}
}
