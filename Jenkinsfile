pipeline {
    agent any
    tools { 
        maven 'Maven 3.3.9' 
        jdk 'jdk8' 
    }
    stages {
          stage ('example') {
            steps {
                sh "echo hello world"
            } 
          }
    }
}
