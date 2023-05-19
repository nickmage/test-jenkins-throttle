pipeline {
    agent any

    stages {
        stage('Sleep Stage') {
            steps {
                script {
                    echo 'Sleeping for 20 seconds...'
                    sleep time: 20, unit: 'SECONDS'
                    echo 'Sleep completed.'
                }
            }
        }
    }
}