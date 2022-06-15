pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Testing in Progress....'
                npm run test:e2e
                echo 'Testing Completed.'
                npm run semantic-release
                echo 'Release completed.'
                npm run build
                echo 'Build completed.'
            }
        }
    }
}
