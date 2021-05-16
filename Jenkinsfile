pipeline {
    agent {
        label 'slave1'
    }
    stages {
        stage ('build'){
            steps {
                sh "mvn clean install"
            }
        }
        stage ('test') {
            steps {
                echo 'this is testing stage'
            }
        }
        stage ('deploy') {
            steps {
                echo 'this is deploystage'
            }
        }
        }
    }



