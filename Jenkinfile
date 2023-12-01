pipeline {
    // agent {
    //     docker { image 'node:20.10.0-alpine3.18' }
    // }

    agent any
    
    environment {
        NAME = 'Jenkinsss'
        PHRASE = 'Good day'
    }

    stages {
        stage('satge-1') {
            steps {
                echo "${PHRASE}, ${NAME}"
            }
        }
        stage('satge-2') {
            steps {
                sh '''
                ls ~ 
                echo 'Hello Test'
                uname -a
                '''
            }
        }
        stage('satge-3') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
