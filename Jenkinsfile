pipeline{
  agent any
    stages{
      stage('dockerfile'){
        echo "Hi Mike"
        sh "docker build -t appimage ."
        sh "docker images"
        sh "docker run appimage"
      }
    }
}
