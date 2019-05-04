// This shows a simple example of how to archive the build output artifacts.
//node {

pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"

                // Rnning Windows cmd with bat
                bat "dir"
                bat "mvn"
            }

        }

    stage ("Create build output") {

           steps {
                echo "Hello World2!"
            }


    }
    
    stage ("Archive build output") {

           steps {
                echo "Hello World3!"
            }

    }



        
    }
}    
    
//}