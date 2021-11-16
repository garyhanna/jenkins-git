pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World Now Later"'
                sh '''
                    echo "Multiline shell steps works too and three"
                    ls -lah
                '''
            }
        }
    }
}
