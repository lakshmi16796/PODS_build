pipeline {
    agent any
    stages {
        stage('Simple Shell Test') {
            steps {
                script {
                    echo "repeat for all your shell steps"
                }
                sh """ 
                    #!/bin/bash
                    echo "This is a test"
                    date
                """
            }
        }
    }
}
