pipeline{
    agent any
    stages{
        stage('Git checkout') {
            steps {
                git branch: 'master', url: 'https://github.com/sivap083/multibranch-pipeline-demo.git'
            }
        }
    }
}
