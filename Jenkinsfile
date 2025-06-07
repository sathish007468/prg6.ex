pipeline {
    agent any
    tools {
        maven 'MAVEN_HOME'   // Make sure this name matches what you configured in Jenkins (case-sensitive)
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
