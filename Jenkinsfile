pipeline{
    agent any
    stages{
        stage("Maven Build"){
            steps{
                sh 'mvn clean package -DskipTests=true'
            }
        }
        stage(" Dev Tomcat Deploy"){
            steps{
                echo "hemanth"
            }
        }
    }
}
