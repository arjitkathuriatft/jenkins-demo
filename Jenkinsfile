pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
//                 bat "mvn -D clean test"
                    echo "I am test"
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