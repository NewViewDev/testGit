pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git branch: 'extra', url: 'https://github.com/NewViewGames/testGit.git'
                script{
                    if (fileExists('RejectIfExists')) {
                        error("RejectIfExists exists. Therefore, failure.")
                    } else {
                        echo("All is fine")
                    }
                }
            }
        }
    }
}
