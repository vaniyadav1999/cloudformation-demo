pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name tcs-auto-stack --template-body file://simplests3cft.json --region 'ap-southeast-1'"
              }
             }
            }
            }
