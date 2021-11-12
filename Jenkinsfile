pipeline {
    agent any {
        stages {
            stage ('Build') {
                cmd 'mvn -B -DskipTests clean package'
            }
            stage('Test') {
                cmd 'mvn test'
            }
        }
    }
}
