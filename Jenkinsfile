pipeline {
    agent { label 'spark' }
    stages {
        stage('Build') {
            steps {
                echo "Testing Jenkins jobs using pipelines"
                sh "bash test_cmd"
                echo "Complete."
            }
        }
    }
}
