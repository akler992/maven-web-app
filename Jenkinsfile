pipeline {  

    agent any
        
    tools{
        maven "Maven-3.9.9"
    }
    stages {
        stage('git Clone') {
            steps {
               git 'https://github.com/ashokitschool/maven-web-app.git'
            }
        }
        stage('maven Build') {
            steps {
               sh 'mvn clean package'
            }
        }
    }
}
