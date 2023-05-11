pipeline {
    // See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
    agent any
    stages {
        stage("Build") {
            steps {
                echo "hello world"
                sh "./gradlew assemble"
            }
        }
        stage("Test") {
            steps {
                sh "./gradlew test"
            }
        }
    }
}
