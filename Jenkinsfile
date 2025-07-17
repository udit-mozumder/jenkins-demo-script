pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/udit-mozumder/jenkins-demo-script.git'
            }
        }
        stage('Run Script') {
            steps {
                sh 'chmod +x hello.sh && ./hello.sh'
            }
        }
    }
}
