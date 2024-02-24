pipeline {
    agent {
        label "agent1"
    }
    stages {
        stage('Deploy') {
            steps {
                script {
                    sh 'docker-compose up -d'
                }
            }
        }
    }
}
