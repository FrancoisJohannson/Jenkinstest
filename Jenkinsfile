// This shows a simple example of how to archive the build output artifacts.
node {

pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
            }



    stage ("Create build output") {
        // Make the output directory.
        bat 'wmic computersystem get name'
        bat "mkdir strangeoutputdirname"

    }
    
    stage ("Archive build output") {
        // Make the output directory.
        bat "mkdir anotherstrangename"

    }



        }
    }
}    
    
}