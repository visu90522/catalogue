pipeline {
    agent { node { label 'AGENT-1' } }
    stages {
        stage('Install depdencies') {
            steps {
                echo "installing"
            }
        }
        stage('Unit test') {
            steps {
                echo "unit testing is done here"
            }
        }
        // stage('Sonar - Scan') {
        //     steps {
        //         sh 'ls -ltr'
        //         sh 'sonar-scanner'
        //     }
        // }
    }
}