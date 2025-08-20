pipeline {
    agent any

    triggers {
        githubPush() // ✅ Auto trigger on GitHub push
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkins!'
            }
        }
    }
}
