pipeline {
    agent any
    
    stages {
        stage ('build') {
            steps {
                sh 'echo Compile'
            }
        }
        
        stage ('stage') {
            steps {
                sh 'echo Test'
            }
        }
        
        stage ('deploy') {
            steps {
                sh 'echo Deploy'
            }
        }
    }
}
