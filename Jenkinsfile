pipeline {
    agent any
     tools {
        maven "Maven3"
      }
    stages {
        stage ('Compile') {
              steps {
            sh 'mvn clean compile'
              }
        }

    }
}
