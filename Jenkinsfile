pipeline {
    agent {
        label 'java-slave'
    }
    environment {
        VALUE_TO = 'production'
    }
    stages {
        stage ('prod stage') {
            when {
                environment name: 'VALUE_TO' , key: 'production'
            }
           
            steps {
                echo "buid when it is meet the production "
            }
        }
    }
}
