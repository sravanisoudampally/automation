
pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh 'go build calculator.go '
            }

            stages {
        stage('test') {
            steps {
                sh 'go test main_test.go '
            }
        }
    }
}
