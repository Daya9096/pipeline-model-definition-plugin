pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Daya9096/pipeline-model-definition-plugin.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
