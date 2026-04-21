pipeline {
    agent any
    stages {
        stage('Checkout') { steps { checkout scm } }
        stage('Analysis') { steps { echo 'Performing code analysis...' } }
    }
}