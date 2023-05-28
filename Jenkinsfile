pipeline {
    agent any
    tools { 
        maven 'maven_3.9.0' 
    }
    
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
