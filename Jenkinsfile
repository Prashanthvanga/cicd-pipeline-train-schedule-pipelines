pipeline {
    agent any 
    stages {
        stage('Gradle Build') { 
            steps {
                 echo 'running build automation'
                 sh './gradlew build'
              archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
        stage('Test') { 
            steps {
                echo 'running build automation test'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'running build automation deploy'
            }
        }
    }
}
