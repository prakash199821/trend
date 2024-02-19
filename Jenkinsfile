pipeline {
    agent { label 'maven'}

environment {
    PATH = "/opt/apache-maven-3.9.2/bin:$PATH"
}

    stages {
        stage("build") {
            steps {
                  echo "-----------Build Started----------"
                sh 'mvn clean deploy'
                  echo "-----------Build Completed------"
            }
        }

