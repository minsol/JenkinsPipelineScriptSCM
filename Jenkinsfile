pipeline {
    agent any

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }

    stages {
        stage('CheckOut') {
            steps {
                echo 'CheckOut'
            }
        }
	stage('Build') {
            steps {
                echo 'Build'
            }
        }
	stage('Archive') {
            steps {
                echo 'Archive'
            }
        }
	stage('Post') {
            steps {
                echo 'Post'
            }
        }
	stage('dsymUpload') {
            steps {
                echo 'DsymUpload'
            }
        }
    }
}