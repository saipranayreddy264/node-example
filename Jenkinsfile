pipeline {
    agent {
        label "java-slave"
    }
    stages {
        stage ('build stage') {
            steps {
                echo "this is a build stage"
            }
        }
    }
    post {
        success {
            echo "post the sucess is trigged"

        }
        failure {
            echo "failure is trigger"


        }
        always {
            echo "sucess is triggered"

        }
    }
}
