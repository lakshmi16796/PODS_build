pipeline {
    agent any
    stages {
        stage('Simple Shell Test') {
            steps {
                sh '''
                    #!/bin/bash
                    echo "inside shell"
                    cd /home/lakshmi/dell_pods/poky
                    pwd
                    source oe-init-build-env
                '''
            }
        }
    }
}

