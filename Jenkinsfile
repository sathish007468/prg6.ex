pipeline {
    agent any
    tools {
        maven 'MAVEN_HOME'
    }
    stages {
        stage('Build') {
            steps {
                dir('prg6.ex') {
                    bat 'mvn clean install'
                }
            }
        }
    }
}
