pipeline {
    agent any

    stages {
        stage('Deploy Website Two') {
            steps {
                sh '''
                    set -e
                    cp index.html style.css /var/www/website-two/
                '''
            }
        }
    }
}
