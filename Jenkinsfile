pipeline {
    agent any
    tools {
        maven 'Maven 3.8.6' // Use the name of the Maven installation configured in Jenkins
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}


