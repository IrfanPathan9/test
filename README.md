pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
               echo 'Building the apllication......'
            }
        }
        stage('Test') { 
            steps {
                echo 'Testing the apllication......'
            }
        }
        stage('Deploy') { 
            steps {
              echo 'Deploy the apllication......'
            }
        }
    }
}
