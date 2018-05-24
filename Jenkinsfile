pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('compile') {
            steps {
                withMaven(maven: 'maven_3_5_3'){                  
                    bat 'mvn clean compile'
                }
            }
        }
    }
}
