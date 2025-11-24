pipeline {
    agent {
        label 'java-slave'
    }
    parameters {
        string (
            name: 'PERSON',
            defaultValue: 'Sai',
            description: 'what is your name???'
        )
        
    }
    stages {
        stage (parameterstage) {
            steps {
                echo "this is parameter stage by , ${params.PERSON}"
            }
        }
    }
}
