pipeline {
    agent {
        label 'java-slave'
    }
    parameter {
        string (
            name: 'PERSON'
            defaultvalue: 'Sai'
            description: 'what is your name'
        )
        
    }
    stages {
        stage (parameterstage) {
            steps {
                echo "this is parameter stage by sai"
            }
        }
    }
}
