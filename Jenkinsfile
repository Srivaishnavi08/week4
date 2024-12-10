pipeline {
    agent any
    script('Git clone'){
        steps{
            git branch: main, url :https://github.com/Srivaishnavi08;
        }
    }
    scrpit('Java Execution'){
        steps{
            bat 'javac hello.java'
            bat 'java hello'
        }
    }
    script('Python execution'){
        steps{
            bat 'python say.py'
        }
    }
}
            
