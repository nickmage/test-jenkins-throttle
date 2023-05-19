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
                    echo 'Sleeping for 20 seconds...'
                    sleep time: 20, unit: 'SECONDS'
                    echo 'Sleep completed.'
                }
            }
        }
    }
}