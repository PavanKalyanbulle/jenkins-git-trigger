
pipeline {
    agent any

    triggers {
        scm('H/5 * * * *') // Jenkins polls GitHub every 5 mins
    }

    stages {
        stage('Build') {
            steps {
                echo 'Hello! Code changed in GitHub. Build started.'
            }
        }
    }
}
