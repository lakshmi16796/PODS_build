pipeline {
    agent any
    stages {
        stage('Simple Shell Test') {
            steps {
                sh '''#!/bin/bash
                    echo "inside shell"
                    cd /home/lakshmi/dell_pods/poky
                    chown -R jenkins:jenkins /home/lakshmi/dell_pods/poky/
                    echo "ownership changes"
                    pwd
                    source oe-init-build-env
                    #bitbake core-image-pods
                '''
            }
        }
    }
}

