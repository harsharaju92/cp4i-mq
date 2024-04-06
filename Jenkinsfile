pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh "docker build -t testdemo  ."
                sh "docker tag demoupdate depukr/mynginx:testdemo"
            }
        }
        stage('tag the image'){
            steps{
               echo "helo docker"
    }
}
    }
}
