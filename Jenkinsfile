pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                sh 'ls -al',
                sh 'npm --version'
            }
        }
    }
}
