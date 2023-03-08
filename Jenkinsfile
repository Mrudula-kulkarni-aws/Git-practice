pipeline {
    agent any
    stages {
        stage('Create Directory') {
            steps {
                script {
                    def dirPath = "/var/lib/jenkins/workspace"
                    sh "mkdir -p testdir1"
                }
            }
        }
    }
}
