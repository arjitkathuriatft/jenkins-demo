pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
//                 bat "mvn -D clean test"
                    echo "I am test"
                    cd /Users/arjitkathuria/Desktop/Repo/jenkins-slenium-demo/jenkins-demo
                    mvn test

            }
            }

            stage('Deploy') {
                            steps {
                //                 bat "mvn -D clean test"
                                    echo "I am deploy"
                            }
        }

    }

   }