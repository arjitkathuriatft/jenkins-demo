pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
//                 bat "mvn -D clean test"
                    echo "I am test"

            }
            }

            stage('Deploy') {
                            steps {
                //                 bat "mvn -D clean test"
                                    echo "I am deploy"
                            }
        }

        stage('QA') {
                                    steps {
                        //                 bat "mvn -D clean test"
                                            echo "I am QA Testing"
                                    }
                }

    }

   }