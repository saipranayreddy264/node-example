pipeline {
    agent {
        label 'java-slave'
    }

    environment {
        COURSE = "Kubernetes"
        GITHUB_CREDS = credentials('i27devopsb8_github_pat')
    }
    stages {
        stage ('Build') {
            steps {
                echo "My Github Credentials are ${GITHUB_CREDS}"
                echo "My user name is: ${GITHUB_CREDS_USR}"
                echo "MY Password is: ${GITHUB_CREDS_PSW}"
            }
        }
    }
}
