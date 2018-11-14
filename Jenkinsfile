pipeline {
    agent any

    stages {
      
        stage ('Build') {
 
steps {
 
bat "dotnet build --configuration Release"
 
}
            steps {
 
bat "dotnet pack --no-build --output nupkgs"
 
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
