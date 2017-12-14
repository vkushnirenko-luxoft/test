pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'mkdir -p build/reports/111/1.xml'
            }
        }
    }
    post {
        always {
            junit 'build/reports/**/*.xml'
        }
    }
}