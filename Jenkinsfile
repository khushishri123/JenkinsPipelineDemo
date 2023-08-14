pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: 'b8b25933-f6f8-46dd-bafe-c5a735073678', url: 'https://github.com/khushishri123/JenkinsPipelineDemo.git'
            }
        }
    }
}
