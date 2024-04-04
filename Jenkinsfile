pipeline {
    agent any

    stages {
        stage('Initialize Terraform') {
            steps {
                sh 'terraform init -no-color'
            }
        }
    }
}

