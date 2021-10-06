pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat 'dir'
                bat '''del C:\\Users\\ghant\\Desktop\\apache-tomcat-8.5.71\\webapps\\Myproject\\surya.html'''
                bat '''copy "surya.html" "C:/Users/ghant/Desktop/apache-tomcat-8.5.71/webapps/Myproject"'''
            }
        }
    }
}
