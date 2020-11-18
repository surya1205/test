pipeline {
    agent any
    tools{
        maven 'Maven'
    }
    stages {
        stage ('Compile Stage') {

            steps {
                    echo 'maven clean................'
                    sh 'mvn clean compile'
            }
        }

        stage ('Install Stage') {
            steps {
                   echo 'maven install................'
                    sh 'mvn install'
            }
        }
    }
}
