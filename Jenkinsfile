pipeline {
    agent any
  stages {
    stage('version') {
      steps {
        sh 'maven --version'
      }
    }

        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
