pipeline {
    agent any
triggers {
    pollSCM('H/3 * * * *')  // ✅ VALID!
}


    stages {
        stage('Build') {
            steps {
                echo 'Hello! Code changed in GitHub. Build started.'
            }
        }
    }
}
