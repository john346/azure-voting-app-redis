pipeline {
    agent any

    stages {
        stage('Verify Branch') {
            steps {
                pwsh 'Write-Output "$GIT_BRANCH"'
            }
        }
    }
}