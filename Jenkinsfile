pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                bat '''
                    cd HelloFX/Maven/hellofx
                    mvn clean install test
                    '''

            }
        }
    }
}
