pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                // Compile the Java file without specifying an output folder
                bat 'javac src\\com\\example\\JenkinsPipelineDemo.java'
            }
        }

        stage('Run') {
            steps {
                // Run the compiled class using the package name
                bat 'java -cp src com.example.JenkinsPipelineDemo'
            }
        }
    }
}
