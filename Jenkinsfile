pipeline:
  agent: any
  stages:
    - stage: 'Submit Stack'
      steps:
        - script:
            scriptBlock: |
              sh "aws cloudformation create-stack --stack-name nested-stack --template-url https://github.com/kalyani-shah/cloudform/blob/main/nested.yml"
