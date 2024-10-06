<<<<<<< HEAD
pipeline{
    agent any
    }
    stages{
        stage("A"){
            steps{
=======
pipeline {
    agent any
    stages {
        stage("A") {
            steps {
>>>>>>> f38ac3e (pipeline)
                echo "========executing A========"
            }
            post {
                always {
                    echo "========always========"
                }
                success {
                    echo "========A executed successfully========"
                }
                failure {
                    echo "========A execution failed========"
                }
            }
        }
    }
    post {
        always {
            echo "========always========"
        }
        success {
            echo "========pipeline executed successfully========"
        }
        failure {
            echo "========pipeline execution failed========"
        }
    }
}
