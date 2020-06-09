pipeline {
    agent any
    stages {
        stage("Read Variable Set in Gradle") {
            steps {
                sh 'env'
                sh "./gradlew setVariable"
                sh 'env'
            }
        }
    }
}