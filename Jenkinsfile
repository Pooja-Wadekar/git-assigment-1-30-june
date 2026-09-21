pipeline {
    agent {
        label 'jnlp-agent'
    }

    stages {
        stage('Test JNLP Agent') {
            steps {
                sh 'hostname'
                sh 'whoami'
                echo 'Running on JNLP Agent'
            }
        }
    }
}
