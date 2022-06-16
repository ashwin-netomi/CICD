pipeline {
    agent any

    stages {
        stage('Run semantic-release') {
            steps {
                echo 'npm run semantic-release....'
                echo 'start'
                 sh """ #/bin/bash
                            npm -v
                            npm run build
                            npm run semantic-release
                        """
                echo 'Build completed.'
            }
        }
    }
}
