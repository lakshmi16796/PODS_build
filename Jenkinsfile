pipeline {
  agent any
  stages {
	  
   stage('Checkout') {
            steps {
                git credentialsId: 'github_creds', url: 'https://github.com/lakshmi16796/PODS_build.git'
            }
    stage ("Edit")
    {
      steps {
        
        script {
	 		       
	 {
        sh '''#!/bin/bash
	
	echo "inside shell"
	
	
	cd /home/lakshmi/dell_pods/poky
	pwd
	source oe-init-build-env
	pwd
	#rm -rf bitbake.lock
	
	
	#bitbake -c clean core-image-pods
	bitbake core-image-pods
	echo "build triggered" 
		
        '''
	}  
    }
  }
   }
  }
}
