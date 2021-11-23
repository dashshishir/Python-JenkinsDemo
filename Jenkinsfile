pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                     echo 'Building....'
                     sh "python main.py"
                 }
                 }
                 stage('Test') {
                 steps {
                    echo 'Testing.....'
                    sh "python test.py"
                 }
                 }

}