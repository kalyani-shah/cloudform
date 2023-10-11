pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
                script {
                    sh "aws cloudformation create-stack --stack-name nested-stack --template-body file://nested.yml --region ap-south-1"
                }
            }
        }
    }
}
