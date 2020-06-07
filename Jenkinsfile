pipeline {
    agent any
    tools {
        maven 'M2-HOME' 
    }
    stages {
        stage ('Compile Stage') {

            steps {
               
                    bat 'mvn clean compile'
                
            }
        }

        stage ('Testing Stage') {

            steps {
                
                    bat 'mvn test'
               
            }
        }


        stage ('Deployment Stage') {
            steps {
               
                    bat 'mvn deploy'
               
            }
        }
    }
}
