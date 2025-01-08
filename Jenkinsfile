pipeline {
    agent {
        docker {
            image 'maven:3.3.3'
            label 'my-label'
        }
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
