node{
    def IMG_DCK = "stevenxs/trip-service"
    def IMG_TAG = "latest"
    def ECR_CRD = "ecr:us-east-2:aws-ecr-admin-cred"
    def ECR_PATH = "772584673213.dkr.ecr.us-east-2.amazonaws.com/${IMG_DCK}"
    def ECR_URL = "https://${ECR_PATH}"
    def MVV_HOME = tool name: 'Maven-3', type: 'maven'
    def MVN_CMD = "${MVV_HOME}/bin/mvn"

    stage('git clone'){
        git credentialsId: 'git-creds', url: 'https://github.com/Transfer-Organization/transfer'
    }
}


