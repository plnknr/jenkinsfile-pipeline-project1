pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
        stage('test') {
            steps {

                sh 'touch deneme.txt'

            }
        }
        stage('deploy') {
            steps {

                sh 'echo "hello" > deneme.txt'

            }
        }
    }
}