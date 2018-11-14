pipeline {
    agent any

    stages {
       stage ('Build') {
 
steps {
 
bat "dotnet build --configuration Release"
 
}
 
}
        stage ('Build') {
 
steps {
 
bat "dotnet pack --no-build --output d:\nupkgs"
 
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
