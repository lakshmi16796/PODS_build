pipeline {
  agent any
  stages {
	  

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
