pipeline{
    agent any
    tools{
        Node
    }
    stages{
        stage('build'){
            steps{
                sh 'npm install'
                echo 'passed by build stage'
            }
        }
        stage('test'){
            steps{
                echo 'passed by test stage'
            }
        }
    }
}
