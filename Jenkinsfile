pipeline {
    // See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
    agent any
    stages {
        stage("Build") {
            steps {
                echo "Build test"
                sh "./gradlew assemble"
            }
        }
        stage("Test") {
            steps {
                echo "Test test"
                sh "./gradlew test"
            }
        }
    }
}