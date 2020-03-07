pipeline {
    agent any
    stages{
        stage('one'){
            when {
                expression {BRANCH == 'origin/devlop' || BRANCH == 'devlop'  
                }                
            steps{
                echo "devlop"
            }    
            }
        }
    }
}
