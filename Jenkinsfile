pipeline {
    agent any

    stages {
        stage('Run semantic-release') {
            steps {
                echo 'npm run semantic-release....'
                echo $WORKSPACE
                echo 'start'
                 sh """ #/bin/bash
                            npm -v
                            
                        """
                echo 'Build completed.'
            }
        }
    }
}
