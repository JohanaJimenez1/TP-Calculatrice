pipeline {
    agent any  

    stages {
        stage('Build') {  
            steps {
                echo 'Démarrage du build...'
                bat 'node hello.js'
             
            }
        }

        stage('Test') {  
            steps {
                echo 'Running tests...'
                sh 'mvn test'  
            }
        }
}
}
