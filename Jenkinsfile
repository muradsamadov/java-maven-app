// def gv

pipeline {
    agent any
    stages {
        // stage("init") {
        //     steps {
        //         script {
        //             gv = load "script.groovy"
        //         }
        //     }
        // }
        stage("build") {
            steps {
                script {
                    echo "Building the app ..."
                    //gv.buildJar()
                }
            }
        }
        stage("test") {
            steps {
                script {
                    echo "Testing the app ..."
                    //gv.buildImage()
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo "Deploying the app ..."
                    //gv.deployApp()
                }
            }
        }
    }   
}