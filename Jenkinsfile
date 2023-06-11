pipeline {
    agent any
    tools {
        maven 'maven3'
    }
    stages {
        stage("build artifact") {
            steps {
                script {
                   sh 'mvn clean package -DskipTestsS'

                }
            }
        }

    }
}