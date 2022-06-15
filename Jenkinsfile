pipeline {
    agent any

    stages {
        stage('Run semantic-release') {
            steps {
                echo 'npm run semantic-release....'
                npm run semantic-release
                echo 'Build completed.'
            }
        }
    }
}
