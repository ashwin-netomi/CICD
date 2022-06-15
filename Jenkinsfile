pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Testing in Progress....'
                npx run test:e2e
                echo 'Testing Completed.'
                npx run semantic-release
                echo 'Release completed.'
                npx run build
                echo 'Build completed.'
            }
        }
    }
}
