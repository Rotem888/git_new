
pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/Rotem888/git_new.git'
            }
        }
        stage('Run Python') {
                steps {
                     bat 'test.py'
            }
        }
    }
}


