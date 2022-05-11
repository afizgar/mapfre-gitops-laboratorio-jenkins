pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
            }
        }
	stage('Build') {
            steps {
                sh 'echo "Ejemplo shell script"'
                sh '''
                    hostname 
                    ls -la
                '''
            }
        }
    }
}
