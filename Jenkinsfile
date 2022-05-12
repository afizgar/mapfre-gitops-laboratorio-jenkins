pipeline {
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
            }
        }
	stage('Build') {
       	    agent { label 'docker-agent' }
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
