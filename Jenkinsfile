pipeline {
    agent any
    environment {
        PATH = "/opt/maven/bin:$PATH"
    }
    stages {
       stage('Mybuild') {
            steps {
                sh 'mvn clean install'
            }
        }
}
}
 
