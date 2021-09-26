pipeline {
    agent { docker { image 'maven:3.3.3' } }
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
