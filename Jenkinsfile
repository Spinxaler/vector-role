pipeline {
    agent {
        label 'centos
    }

    stages {
        stage('Hello') {
            steps {
                sh 'molecule test'
            }
        }
    }
}
