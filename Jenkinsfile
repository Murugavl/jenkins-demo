pipeline {

    agent any

    stages {

        stage('Read File') {
            steps {
                sh 'cat message.txt'
            }
        }

        stage('Build') {
            steps {
                echo 'Build completed successfully!'
            }
        }

    }
}
