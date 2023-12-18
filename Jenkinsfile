pipeline {
agent any
stages {   
    stage ('install'){
        steps {
            sh 'pip install pytest'
        }
    }

        stage ('Test'){
        steps {
            sh 'python -m pytest'
        }
    }
}
}
