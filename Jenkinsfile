pipeline {

    agent any
triggers {
    pollSCM('H/1 * * * *')  // ✅ VALID!
}


    stages {
        stage('Build') {
            steps {
                echo ello! Code cssshanged in GitHub. Build started.'
            }
        }
    }
}
