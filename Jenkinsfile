pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java sds source code'
                sh 'javac hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java hello'
            }
        }
    }
}
