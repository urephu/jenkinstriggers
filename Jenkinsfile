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
                
            }
        }
        stage('Build') {
            steps {
                echo 'Building Artifact' 
                
            }
        }
    }
}    