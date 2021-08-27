pipeline {
    agent any 
    stages {
		stage('Checkout_Git') { 
            steps {
                echo "Checking out from Git repository";
            }
        }
        stage('Build') { 
            steps {
                echo "Build Stage";
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy Stage";
            }
        }
        stage('Quality') { 
            steps {
                echo "Quality Stage";
            }
        }
		stage('Unit') { 
            steps {
                echo "Unit Test Stage";
            }
        }
    }
}
