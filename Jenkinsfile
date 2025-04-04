pipeline {
    agent any
    stages {
        stage('One') {
            steps {
                script {
                    def start = System.currentTimeMillis()
                    echo 'Hi, welcome to pipeline demo....'
                    sleep 1  // Adding a delay
                    def end = System.currentTimeMillis()
                    echo "Stage One Duration: ${(end - start)}ms"
                }
            }
        }
        stage('Two') {
            steps {
                script {
                    def start = System.currentTimeMillis()
                    echo 'Sample testing of Stage 2'
                    sleep 1
                    def end = System.currentTimeMillis()
                    echo "Stage Two Duration: ${(end - start)}ms"
                }
            }
        }
        stage('Three') {
            steps {
                script {
                    def start = System.currentTimeMillis()
                    echo 'Thanks for using Jenkins Pipeline'
                    sleep 1
                    def end = System.currentTimeMillis()
                    echo "Stage Three Duration: ${(end - start)}ms"
                }
            }
        }
    }
}
