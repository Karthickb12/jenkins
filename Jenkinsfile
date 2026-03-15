pipeline {
agent any


stages {

    stage('Clone Repository') {
        steps {
            echo 'Cloning code from GitHub...'
            git 'https://github.com/sample-user/sample-project.git'
        }
    }

    stage('Build') {
        steps {
            echo 'Building the project...'
        }
    }

    stage('Test') {
        steps {
            echo 'Running tests...'
        }
    }

    stage('Deploy') {
        steps {
            echo 'Deploying application...'
        }
    }

}

}
