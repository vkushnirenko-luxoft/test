pipeline {
    agent { docker 'slave:v.1' }
    stages {
        stage('build') {
            steps {
                sh 'cat /etc/os-release'
            }
        }
    }
}