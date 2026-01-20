
pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo "Cloning source code..."
            }
        }

        stage('Build') {
            steps {
                echo "Build step (for Java/Node projects build here)"
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                bat 'xcopy index.html C:\\deploy\\ /Y'
            }
        }
    }
}
