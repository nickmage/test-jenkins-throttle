pipeline {
    agent any

    stages {
        stage('Sleep Stage') {
            steps {
                script {
                    echo 'Sleeping for 30 seconds...'
                    sleep time: 30, unit: 'SECONDS'
                    echo 'Sleep completed.'
                }
            }
        }
    }
}