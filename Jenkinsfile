
pipeline {
    agent any

    stages {
        stage('mod downlod') {
            steps {
                sh 'go mod download'
            }
        }
        stage('build') {
            steps {
                sh 'go build calculator.go '
            }
        }
        stage('test') {
            steps {
                sh 'go test main_test.go '
            }
        }
    }
}
               
            
        
