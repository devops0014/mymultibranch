pipeline {
    agent any
    stages {
        stage ("code") {
            steps {
                echo "hey code is done"
            }
        }
        stage ("Build") {
            steps {
                echo "hey Build is done"
            }
        }
        stage ("deploy_to_test") {
            steps {
                echo "hey Deployment is done on TEST env"
            }
        }
        stage ("deploy_to_prod") {
            steps {
                echo "hey Deployment is done on PROD env"
            }
        }
    }
}
