pipeline {
    agent any
    stages {
        stage('ninit'){
            steps {
                sh 'terraform init'
            }
        }
        stage(formst){
            steps{
                sh 'terraform fmt'
            }
        }
        stage(validate){
            steps{
                sh 'terraform validate'
            }
        }
        stage(plan){
            steps{
                sh 'terraform plan'
            }
        }
        stage(destroy){
            steps{
                sh 'terraform destroy --auto-approve'
            }
        }

        }
}
    

            
             

    

    
        
        

