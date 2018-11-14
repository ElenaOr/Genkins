pipeline {
    agent any

    stages {
      
       stage ('Build') {
 
steps {
 
bat "dotnet build --configuration Debug"
 
}
 
}
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
