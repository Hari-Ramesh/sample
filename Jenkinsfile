@Library('shared_library') _
pipeline {
    agent any

    stages {
        stage('source checkout') {
            steps {
                src("https://github.com/Hari-Ramesh/jenkins_shared_library.git", "main")
            }
        }
    }
}
