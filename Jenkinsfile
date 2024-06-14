pipeline {
    agent any
    stages {
        stage("Compile") {
            steps {
                sh "./gradlew compileJava"
            }
        }
        stage("Unit tests2"){
            steps {
                sh "./gradlew test"
            }
        }
    }
}