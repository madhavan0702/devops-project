pipeline {
    agent any
    stages {
        stage('Compile Java Code') {
            steps {
                bat 'javac HelloWorld.java'  // Use 'bat' instead of 'sh'
            }
        }
        stage('Run Java Application') {
            steps {
                bat 'java HelloWorld'  // Use 'bat' for Windows
            }
        }
    }
}