pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'application is building'
            }
        }
        stage('testing') {
            steps {
                echo 'Automation Testing'
            }
        }
        stage('UAT') {
            steps {
                echo 'waiting for UAT'
            }
        }
        stage('release') {
            steps {
                echo 'application is ready to releaseto prod services'
            }
        }
    }
}
