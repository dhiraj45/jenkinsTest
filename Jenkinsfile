pipeline {
    agent any
    
    stages {
        stage('build')
        {
            steps{
                echo 'Build App'
            }
        }
        stage('Test') {
            steps {
                echo 'Test App'
            }
        }
        stage('Deploy'){
            steps{
              sh 'python mossad.py'
            }
        }
    }
}
