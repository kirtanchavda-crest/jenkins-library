@Library('jenkins-library@main') _

pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
                gitCheckout(
                    branch: "main",
                    url: "https://github.com/kirtanchavda-crest/jenkins-library.git"
                )
            }
        }
        stage('Hello'){
            steps{
                sayHello 'Kirtan'
            }
        }
    }
}
