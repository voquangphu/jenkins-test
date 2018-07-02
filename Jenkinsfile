pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
		sh 'isFoo is ' + params.branch
            }
        }
    }
}
