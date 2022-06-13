pipeline {
    agent any

    stages {
        stage('checkout data from Jenkinsfile') {
            steps {
                echo 'Downloaded the data from git'
            }
        }
        stage('Buid') {
            steps {
                echo 'buid stage'
            }
        }
        stage('Test') {
            steps {
                echo 'Test stage'
            }
        }
        stage('Deploy') {
            steps {
                echo "Selected option is --> ${action}"
            }
        }
    }
}
