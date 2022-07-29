pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                echo "Hello"
            }
        }
        
        stage('maven build'){
            steps{
                sh 'mvn package'
            }
        }
        
        
    }
}
