pipeline {
    agent {label 'ansible'}

    stages {
        stage('Hello') {
            steps {
                println 'Hello World'
            }
        }
        stage('ansible') {
            steps {
                sh 'ansible-playbook test.yml'
            }
        }
        
    }
}
