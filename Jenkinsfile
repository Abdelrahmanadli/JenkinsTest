pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                echo 'Compiling...'
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Starting application...'
                // Replace nohup with start
                bat 'start /B java -jar HelloWorld.jar'
            }
        }
    }
}
