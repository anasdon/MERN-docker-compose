pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Client Tests') {
    	    steps {
        	dir('mern/fromtend') {
            	    sh 'npm install'
        	}
    	    }
        }
    }
}
