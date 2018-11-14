pipeline {
    agent any

    stages {
      
        stage ('Build') {
 
steps {
steps {
 
bat "dotnet build --configuration Release"
 
}
 
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
