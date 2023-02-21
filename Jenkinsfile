pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://vpc_creation.yml --region 'us-east-1'"
              }
             }
            }
            }