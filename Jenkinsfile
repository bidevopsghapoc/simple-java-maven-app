pipeline {
    agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }

        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
