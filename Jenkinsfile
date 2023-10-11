pipeline{
	agents any
	stages{
		stage('Submit Stack'){
			steps{
			sh "aws cloudformation create-stack --stack-name nested-stack --template-body file://nested.yml"
			}
		}
	}
}

