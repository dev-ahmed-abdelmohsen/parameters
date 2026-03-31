pipeline {
    agent any

    parameters {
        choice(
            name: 'ENV',
            choices: ['dev', 'stg', 'prod'],
            description: 'Choose environment'
        )
    }

    stages {
        stage('Print Env') {
            steps {
                echo "Environment is ${params.ENV}"
            }
        }
    }
}
