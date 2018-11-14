pipeline {
    agent any

    stages {
      
        stage ('Build') {
 
steps {
 
bat "dotnet pack --no-build --output mypackage"
 
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
