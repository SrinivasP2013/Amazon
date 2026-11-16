pipeline {

agent any

stages{

stage('checkout'){
steps {
git branch:'main'
url:'url'
}
}

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/SrinivasP2013/Amazon.git'
            }
        }

        stage('Maven Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
