pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat 'dir'
                bat '''copy "index.html" "C:/Users/Admin/Desktop/apache-tomcat-9.0.54/webapps/"'''
                bat '''C:/Users/Admin/Desktop/apache-tomcat-9.0.54/bin/startup'''
            }
        }
    }
}
