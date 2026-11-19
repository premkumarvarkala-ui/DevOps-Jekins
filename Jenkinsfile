pipeline {
    agent {
        label "worker-1"
    }

    stages {
        stage("checkoutstage") {
            steps {
                sh '''
                    echo "hello pipeline"
                '''
            }
        }
    }
}