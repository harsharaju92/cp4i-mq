pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh "docker build -t testdemo  ."
                sh "docker tag demoupdate depukr/mynginx:testdemo
                sh "docker push depukr/mynginx:testdemo"
"
            }
        }
    }
}
