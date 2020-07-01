
//Jenkinsfile (Declarative Pipeline)

pipeline {

    agent any
    
    environment {
    
    	JAVA_HOME = '/usr/lib/jvm/java-11-openjdk-amd64'
    
    }
    
    stages {
        stage('build') {
            steps {
                echo 'Compilant...'               
            }
            steps {                
                sh 'mvn --version'
            }
            steps {                
                sh 'mvn clean compile'
            }

        }
    }
}

