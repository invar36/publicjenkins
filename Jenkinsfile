pipeline {
    agent any
    stages {
        stage('Hello World') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "basic multi line sh"
                    
                '''
            }
        }
        stage('Hello Team'){
            steps {
                sh 'echo "Hello Team"'
            }
        }
    }
}
