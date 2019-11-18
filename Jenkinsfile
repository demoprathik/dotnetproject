pipeline {
  agent agent`  {label 'linuxslave'}
  stages {
  stage('checkout') {
  steps {
    script {
     bat 'dotnet Build'
     bat 'dotnet clean --no-incremental'
}
}
}
}
}
