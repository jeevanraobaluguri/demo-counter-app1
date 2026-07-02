pipeline{

    agent any
    
    stages{
    
        stage ('git checkout'){
        
            steps
            {
                git branch: 'main', url: 'https://github.com/jeevanraobaluguri/demo-counter-app1.git'
            }

        }

        stage ('Unit Testing'){
        
            steps
            {
                sh 'mvn '
            }

        }


    }

}