pipeline {
    stages {
        stage('Build') { 
            steps {
                mvn -B -DskipTests clean package
            }
        }
    }
}