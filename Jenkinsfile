pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                bat "mvn validate"
            }
        }        
        stage('maven build'){
            steps{
                bat "mvn compile"
            }
        }
        stage('Git clone'){
            steps{
                bat "mvn test"
            }
        }
        stage('Git clone'){
            steps{
                bat "mvn package"
            }
        }
        stage('Git clone'){
            steps{
                bat "mvn verify"
            }
        }
         stage('Git clone'){
            steps{
                bat "mvn install"
            }
        }
         stage('Git clone'){
            steps{
                bat "mvn compile"
            }
        }     
    }
}
