pipeline {
    agent any

    stages {
        stage('OS Version') {
            steps {
                echo 'Terraform version..'
                sh "cat /etc/*release"
            }
        }
        stage ("create directory") {
            steps {
                sh "mkdir /tmp/data1"
            }
        }
        stage (" Action") {
            steps {
                echo "Terraform action is --> ${action}"
                 
           }
        }
    }
}
