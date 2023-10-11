pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
                script {
                    sh "aws cloudformation create-stack --stack-name nested-stack --template-url https://github.com/kalyani-shah/cloudform/raw/main/nested.yml"
                }
            }
        }
    }
}
