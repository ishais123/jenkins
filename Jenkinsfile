pipeline {
    agent {label 'ansible'}

    stages {
        stage('Hello') {
            steps {
                println "Hello ${name}"
            }
        }
        stage('ansible') {
            steps {
                sh 'ansible-playbook test.yml'
            }
        }
        
    }
}
