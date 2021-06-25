    pipeline {
        agent any
        
        tools {nodejs "node"}
        stages {
            stage('Build') {
                steps {
                    // git branch: 'main', credentialsId: 'Tanzil', url: 'https://github.com/newageproductsgit/next-nap.git'
                    git branch: 'main', credentialsId: 'Tanzil', url: 'https://github.com/tanzilansari/next-js-docker.git'
                }
            }
        }
    }