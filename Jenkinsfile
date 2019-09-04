pipeline {
    agent {
        docker {
            image 'demomav/jenkinsbuild:16'
            
        }
    }
    stages {
        stage('validate') {
            steps {
                sh 'mvn -B'
            }
        }
    }
}
