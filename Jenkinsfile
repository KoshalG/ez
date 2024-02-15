pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        always {
            emailext body: 'LOL', subject: 'LOL', to: 'guptakoshal1@gmail.com'
        }
    }
}
