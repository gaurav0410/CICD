pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
            steps {
                sh 'printenv'
                bat "mvn package"
                sh 'mvn clean compile'
            }
        }
    }
        stage ('Testing Stage') {
            steps {
                sh 'mvn test'
                }
            }
        }
        stage ('Deployment Stage') {
            steps {
                sh 'mvn install'
    }
} 
