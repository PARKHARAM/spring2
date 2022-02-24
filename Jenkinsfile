pipeline {
    agent any

    tools {
        terraform 'Terraform14'
        maven('maven3.0.5')

    }
    stages{
       stage('Git Checkout') {
           steps {
                git branch: 'main', credentialsId: 'gkfka133', url: 'https://github.com/PARKHARAM/vmcreate-terraform' 
         }      
        }
        


        

    }
}
