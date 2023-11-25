

pipeline {
    agent any
    stages {
        stage('Example') {
            agent any
            steps {
                echo 'Hello World'
                sh "docker build -t appimage ."
                sh "docker images"
                sh "docker -it run appimage"
            }
        }
    }
}
