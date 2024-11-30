pipeline {
    agent any
    
    tools {
        maven "maven-3.9.9"
    }

    stages {
        stage('Git Clone IS FIRST') {
            steps {
                git 'https://github.com/ashokitschool/maven-web-app.git'
            }
        }
        stage('Maven Build IS SECOND') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
