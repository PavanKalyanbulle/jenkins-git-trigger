pipeline {

    agent any
triggers {
    pollSCM('H/1 * * * *')  // ✅ VALID!
}


    stages {
        stage('Build') {
            steps {
                echo 'Hello! Code cssshanged in GitHub. Build started.'
            }
        }
    }
}
