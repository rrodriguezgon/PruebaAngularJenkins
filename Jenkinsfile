pipeline{
    agent any
    stages {
        stage('Checkout-git'){
            steps{
                git branch: 'main', poll: true, url: 'https://github.com/rrodriguezgon/PruebaAngularJenkins.git'
            }
        } 
        stage('test'){
            steps {
                echo 'Testing...'
            }
        }
    }
}