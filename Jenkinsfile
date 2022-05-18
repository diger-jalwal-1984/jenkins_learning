pipeline {
    agent any 
    
    stages {
        stage('build') {
            when {
                tag "release-*"
            }
            steps {
                echo 'Hello World building tag'
            }
        }
    }
}
