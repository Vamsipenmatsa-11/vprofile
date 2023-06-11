pipeline{
    agent any
    stages{
        stage("build artifact"){
            sh 'mvn clean package -DskipTestsS'
        }

    }
}