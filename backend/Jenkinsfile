pipeline {
    agent any
    
    options {
        skipDefaultCheckout(true)
     }
    

    stages {
        stage('Code PUSH') {
            steps {
               git branch: 'main', 
                   url: 'https://github.com/Isharohira/Wanderlust-CI-CD-Project.git',
                   credentialsId: 'github-cred'
            }
        }

    }
}
