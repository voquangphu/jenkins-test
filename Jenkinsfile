pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
		sh sh 'isFoo is ' + params.branch
            }
        }
    }
}
