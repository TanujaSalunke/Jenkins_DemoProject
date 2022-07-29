pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                bat "mvn compile"
            }
        }
        
        stage('maven build'){
            steps{
                bat "mvn package"
            }
        }
        
        
    }
}
