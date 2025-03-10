pipeline {
    agent any 

    environment {
        DOCKER_CREDENTIALS_ID = balavva12
        DOCKER_IMAGE = 'balavva12/todo-application:latest'
    }

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'master',
            url: https://github.com/Balavva12/todo-application.git
            }
        }   
    }
}
