pipeline {
    agent any

    stages {
        stage('Sleep Stage') {
            steps {
                script {
                    echo 'Sleeping for 60 seconds...'
                    sleep time: 60, unit: 'SECONDS'
                    echo 'Sleep completed.'
                }
            }
        }
    }
}