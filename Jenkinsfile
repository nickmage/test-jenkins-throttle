pipeline {
    agent any

    // Throttle a declarative pipeline via options
    options {
      throttleJobProperty(
          categories: ['test_throttle'],
          throttleEnabled: true,
          throttleOption: 'category'
      )
    }

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