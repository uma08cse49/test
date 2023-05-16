pipeline {
    agent any

stages {
        stage('Build') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: '5eaa1702-3ebd-493d-92c8-5891bf96ac72', url: 'https://github.com/uma08cse49/test.git']])
 
            }
        }
    }
}

    stages {
        stage('Build') {
            steps {
                git branch: 'main', credentialsId: '5eaa1702-3ebd-493d-92c8-5891bf96ac72', url: 'https://github.com/uma08cse49/test.git'
 
            }
        }
    }
}
