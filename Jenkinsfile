pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, keepAll: false, reportDir: '', reportFiles: 'regi.html', reportName: 'HTML Report', reportTitles: '', useWrapperFileDirectly: true])'
            }
        }
    }
}
