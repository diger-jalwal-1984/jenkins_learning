pipeline {
    agent any 
    
    stages {
        stage('build') {
            when {
                tag "2.0"
            }
            steps {
                echo 'Hello World building tag'
            }
        }
    }
}
