pipeline {
    agent any 
    stages {
        stage('Build') { 
           steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls
                '''
            }
        }
        stage('Test') { 
            steps {
                echo "this is test"
            }
        }
        stage('Deploy1') { 
            steps {
                echo "this is test" 
            }
        }
		stage('Deploy2') { 
            steps {
                echo "this is test" 
            }
        }
    }
}