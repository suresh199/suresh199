pipeline {

    agent any
	
	
	
	
 stages {
      stage('checkout') {
           steps {
             
                git branch: 'master', url: 'https://github.com/suresh199318/kubernetes_deploy.git'
             
          }
        }
	 stage('Execute Maven') {
           steps {
             
                sh 'ls -la'             
		sh 'pwd && whoami && ls'
          }
        }
        
    
  
  
     }
     
     post {
        // Clean after build
        always {
            cleanWs()
        }
  }
	}
