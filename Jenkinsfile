@Library('jenkins-shared-library') _

pipeline{

    agent any
    
    stages{

        stage('Git Checkout')

            steps{

                script{
                    
                    gitCheckout{
                        branch: "main",
                        url: "https://github.com/PraveenReddy-Lingala/JAVA_APPLICATION_Mr-Praveen.git"

                    }
                }
            }
    
    }
}