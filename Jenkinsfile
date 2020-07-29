pipeline {
    agent any
    tools {
    maven 'jenkins-maven'
  }
    stages {
        stage('Hello') {
            steps {
                sh'mvn clean install -Dskiptests'
            }
        }
    }
}
