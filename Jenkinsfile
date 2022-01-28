pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'whoami'
                sh 'pwd'
                sh 'ls -lsa'
                sh 'node --version'
                sh 'npm init'
                sh 'npm install --save lodash'
            }
        }
    }
}
