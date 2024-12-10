pipeline {
    agent any
    stages{
        stage('Git clone'){
            steps{
                git branch: main, url :https://github.com/Srivaishnavi08;
            }
        }
        stage('Java Execution'){
            steps{
                bat 'javac hello.java'
                bat 'java hello'
            }
        }
        stage('Python execution'){
            steps{
                bat 'python say.py'
            }
        }
    }
}
            
