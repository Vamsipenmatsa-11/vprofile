pipeline{
    agent any
    stages{
        stage("build artifact"){
            steps{
                script{
                   sh 'mvn clean package -DskipTestsS'

                }
            }
        }

    }
}