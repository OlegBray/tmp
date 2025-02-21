pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Going to run hello_world.py'
                bat 'python hello_world.py'
            }
        }
        stage('Hello Again') {
            steps {
                echo 'Going to run hello_world.py'
                bat 'python hello_world.py'
            }
        }
    }
}
