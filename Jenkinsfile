pipeline {
    agent any
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                echo "Hello World"
            }
        }
        stage('Test') {
            steps {
                echo "Hello World"
            }
        }
        stage('Deliver for development') {
            when {
                branch 'development' 
            }
            steps {
                echo "Hello World"
                input message: 'Finished using the web site? (Click "Proceed" to continue)'
                echo "Hello World"
            }
        }
        stage('Deploy for production') {
            when {
                branch 'production'  
            }
            steps {
                echo "Hello World"
                input message: 'Finished using the web site? (Click "Proceed" to continue)'
                echo "Hello World"
            }
        }
    }
}
