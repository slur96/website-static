pipeline{

    agent any

    stages{

        stage("Git Checkout"){
            steps{
                git branch: 'master', url: 'https://github.com/slur96/website-static'
            }  
        }
        stage("Unit Testing"){
            steps{
                sh 'mvn test'
            }  
        }
    }
}