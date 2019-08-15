pipeline {
    agent any
     tools {
        maven "apache-maven-3.5.0"
      }
    stages {
        stage ('Compile') {
              steps {
            sh 'mvn clean compile'
              }
        }

    }
}
