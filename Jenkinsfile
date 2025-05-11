pipeline {
    agent any

    stages {
        stage("compile"){
            steps {
                step {
                    sh 'javac Test.java'
                }
            }
            
        }

        stage("run"){
            steps {
                step {
                    sh 'java Test'
                }
            }
        }
    }
}