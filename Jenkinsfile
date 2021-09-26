pipeline {
    agent any
    properties([parameters([string(defaultValue: 'us-east-1', name: 'region')])])
    stages {
        stage('build') {
            steps {
                sh 'echo "test"'
            }
        }
        stage('test_parameter') {
          steps {
              script {
              sh """
              sh bash.sh
              """
              }
         }
       }
    }
}
