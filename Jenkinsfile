@Library('jenkins-shared-library') _
pipeline{

    agent any

    stages{

        stage('Git Checkout'){

            steps{


                    gitCheckout(
                        branch: "main",
                        url: "https://github.com/PraveenReddy-Lingala/JAVA_APPLICATION_Mr-Praveen.git"

                    )
            }
        }
        stage('Unit test mvn'){

            steps{
                script{
                    
                    mvnTest()
                }
            }
        }
    }
}