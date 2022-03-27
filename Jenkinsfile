pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                sh "git 'https://github.com/NewViewGames/testGit.git'"
                sh "git pull"
//                 sh "cat 'New Text Document.txt'"
                sh "pwd"
            }
        }
    }
}
