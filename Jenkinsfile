pipeline {
    agent {
        label ('java-slave')
    }
    // define envinronmentsl variables
    environment {
        name = "sai"
        course = "jenkins"
    }
    stages {
        stage ('Build stage') {
            steps {
                echo ("this is the building")
                echo ("welcome to ${cousre} classes")
                echo ("this is done by ${name}")

            }
        }
    }
}
