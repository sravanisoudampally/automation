
pipeline {
    agent any

    stages {


        stage('Fetch Dependencies') {
            steps {
                sh 'go mod download'
            }
            stage('Fetch Dependencies') {
            steps {
                sh 'go sum download'
            }
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
            }    
            
