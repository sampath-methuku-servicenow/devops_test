pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Step -- Testing1   '
            }
        }
        stage('Test') {
            steps {
                echo 'Test Step  -- Testing2  '
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Step'
                 snDevOpsChange();
                
            }
        }
    }
}
