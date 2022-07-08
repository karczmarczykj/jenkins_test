pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hellow World"'
                sh '''
                    echo "Multiline shell steps should works too"
                    ls -lah
                '''
            }
        }
    }
}
