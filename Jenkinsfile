pipeline {
    agent any 
    stages {
        stage('Gradle Build') { 
            steps {
                 sh './gradlew clean build'
              archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
        stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
}
