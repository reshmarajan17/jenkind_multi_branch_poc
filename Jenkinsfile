pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
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
