pipeline{
    tools 
{}
stages {
        stage('Checkout') {
            steps {
                Checkout scm
            }
        }
        stage('Test') {
            steps {
                sh'sudo apt install npm'
                sh 'npm test'
            }
        }
        stage('Build') {
            steps {
                echo 'npm run build'
            }
        }
    }
   
}