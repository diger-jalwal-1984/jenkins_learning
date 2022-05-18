pipeline {
    agent any 
    
    stages {
        stage('build') {
            when {
                buildingTag()
            }
            steps {
                echo 'Hello World building tag'
            }
        }
    }
}