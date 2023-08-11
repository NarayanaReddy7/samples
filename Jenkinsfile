pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                bat 'C:\ProgramData\Jenkins\.jenkins\workspace\sample\HelloFX\Maven\hellofx'
                bat 'mvn clean'
            }
        }
    }
}
