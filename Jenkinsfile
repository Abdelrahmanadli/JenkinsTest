pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Compiling...'
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {a
                echo 'Running...'
                sh 'java HelloWorld'
            }
        }
    }
}
