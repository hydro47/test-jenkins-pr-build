pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh '''#!/bin/bash -l
                    echo $0
                    #moar stuff I needed to do
                    #like use rvm, which doesn't work with shell, it needs bash.
                    '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
