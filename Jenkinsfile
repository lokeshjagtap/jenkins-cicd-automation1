pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac -d out src/main/java/com/example/JenkinsPipelineDemo.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java -cp out com.example.JenkinsPipelineDemo'
            }
        }
    }
}