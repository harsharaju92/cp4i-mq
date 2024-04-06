pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh "docker build -t testdemo  ."
                
                
"
            }
        }
        stage('tag the image'){
            steps{
                sh "docker tag demoupdate depukr/mynginx:testdemo"
    }
}
    }
}
