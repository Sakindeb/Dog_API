pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'newman run Dog API Tests.postman_collection.json'
            }
        }
        
        
    }
}
