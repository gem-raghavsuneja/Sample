pipeline {
    agent any

    stages {
        stage('This is a sample step 1') {
            steps {
              build 'HEEEE'
            }
        }
    }
    post{
        always{
            emailext body: 'Hello', subject: 'Pipeline status', to: 'testsuneja123@gmail.com'
        }
    }
}
