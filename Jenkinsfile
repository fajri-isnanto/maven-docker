pipeline {
    agent any
    tools{
        jdk 'OpenJDK11'
        maven 'Maven3'
    }

    stages {
        stage ('Build Jar by Maven') {
            steps {
                sh 'mvn -B -DskipTests clean install' 
            }
        }
    }
}