pipeline {
    agent any

    stages {
        stage('valiate') {
            steps {
                echo 'validating..'
                sh 'mvn validate'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'mvn test'
            }
        }

    }
}
