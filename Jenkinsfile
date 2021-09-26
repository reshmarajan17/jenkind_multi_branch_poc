pipeline {
    agent any
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
