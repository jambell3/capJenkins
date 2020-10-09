pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Goodbye') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Verify') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        
    }
}
