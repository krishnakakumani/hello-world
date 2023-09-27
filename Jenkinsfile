pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World from'
            }
        }
    }
    post { 
        always { 
            echo 'Running after the stages'
        }
    }
}
