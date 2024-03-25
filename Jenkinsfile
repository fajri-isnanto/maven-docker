pipeline {
    agent any

    stages {
        stage ('Build Jar by Maven') {
            steps {
                sh 'mvn -B -DskipTests clean install' 
            }
        }
    }
}