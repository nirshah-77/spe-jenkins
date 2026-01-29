pipeline { 
agent any
    stages {
        stage('Build Code') {
            steps {
                bat "python3 prog1.py"
                }
        }
       stage('Test Code') {
            steps {
                bat "python3 Test.py"
            }
        }
    }
}
