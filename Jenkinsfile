pipeline {
    agent any
    stages {
        stage('Test Write Access') {
            steps {
                sh '''
                    echo "Testing file write" > /var/lib/jenkins/workspace/pods_build/testfile.txt
                    cat /var/lib/jenkins/workspace/pods_build/testfile.txt
                '''
            }
        }
    }
}
