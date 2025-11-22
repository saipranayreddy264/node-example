pipeline {
    agent {
        label 'java-slave'
    }
    environment {
        GITHUB_CREDS = credentials('saipranay_github_pat')
    }
    stages {
        stage ('build stage') {
            steps {
                echo ("my github credentials are ${GITHUB_CREDS}")
                echo ("my github user name is ${GITHUB_USR}")
                echo ("my github password is ${GITHUB_PSW}")
            }
        }
    }
}
