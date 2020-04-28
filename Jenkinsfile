pipeline {
    //agent { dockerfile true }
     //args '--entrypoint=\'\''
    agent {
        dockerfile {
            args '--entrypoint=\'\''
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'java -version'
                sh "hello from the other side"
            }
        }
    }
}
