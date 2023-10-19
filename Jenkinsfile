pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'newman run Dog API Tests.postman_collection.json'
            }
        }
        
    }
}
