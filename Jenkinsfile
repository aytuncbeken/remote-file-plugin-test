pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Hello!'
            }
        }
        stage('Branch') {
            steps {
                echo "Branch is: ${env.RJPP_BRANCH}"
            }
        }
    }
}
