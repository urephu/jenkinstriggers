pipeline {
    agent any 
    stages {
        stage('list envr var') {
            steps {
                echo 'printing variables' 
                sh "printenv |  sort"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Artifact' 
                sh "mvn test"
            }
        }
        stage('Build') {
            steps {
                echo 'Building Artifact' 
                sh "mvn install"
            }
        }
    }
}    