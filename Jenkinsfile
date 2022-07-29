pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                git 'https://github.com/TanujaSalunke/Jenkins_DemoProject.git'
            }
        }
        
        stage('maven build'){
            steps{
                sh 'mvn package'
            }
        }
        
        
    }
}
