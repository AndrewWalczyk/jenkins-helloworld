pipeline {
    agent any   
    stages {   
        
       stage('build') {
            steps {
                echo "Backpocket demo"
            }
        }

        stage('Test image') {
         /* This stage runs unit tests on the image; we are
            just running dummy tests here */
            steps {
                sh 'echo "Tests successful"'
          }
        }     
    }
}
