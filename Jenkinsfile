pipeline {
    agent any
    stages {
        stage("Edit") {
            steps {
                script {
                    dir("/home/lakshmi/dell_pods/poky") {
                        sh '''
                            #!/bin/bash
                            echo "inside shell"
                            ls -l /home/lakshmi/dell_pods/poky
                            #cd /home/lakshmi/dell_pods/poky
                            #pwd
                            #source oe-init-build-env
                            #pwd
                            #rm -rf bitbake.lock
                            #bitbake -c clean core-image-pods
                            #bitbake core-image-pods
                            #echo "build triggered"
                        '''
                    }
                }
            }
        }
    }
}
