
pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/Rotem888/gitproject.git'
            }
        }
        stage('Run Python') {
                steps {
                     bat 'test.py'
            }
        }
    }
}
