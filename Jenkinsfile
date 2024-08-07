properties([parameters([string(defaultValue: 'aws-us', name: 'DISK_NAME'), string(defaultValue: 'machine', name: 'MACHINE_NAME'), string(defaultValue: '1000', name: 'TARGET_GB')])])

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
                     bat 'getenv.py'
            }
        }
    }
}
