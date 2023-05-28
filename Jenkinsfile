pipeline {
    agent any
    tools { 
        maven 'maven_3_9_0' 
    }
    
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
