
//Jenkinsfile (Declarative Pipeline)

pipeline {

    agent any
    
    environment {
    
    	JAVA_HOME = '/usr/lib/jvm/java-11-openjdk-amd64'
    
    }
    
    stages {
        stage('Compilant') {
            steps {
                echo 'Compilant...'  
                sh 'mvn --version'
                sh 'mvn clean compile'             
            }
        }
        stage('Testejant') {
            steps {
                echo 'Testejant...'  
          
            }
        }
    }
}

