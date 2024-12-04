pipeline {
    agent any

    stages {
        stage('one') {
            steps {
                echo 'building application'
                echo 'This is first stage'
            }
        }
        stage('Two') {
            steps {
                echo 'testing application'
            }
        }
        stage('Three') {
            steps {
                echo 'deploying application'
            }
       }
    }
}
