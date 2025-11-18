node {
    stage('Build') {
        // Use the Maven image
        docker.image('maven:3.9.11-eclipse-temurin-21-alpine').inside('-v C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\My-Pipeline_main:/workspace -w /workspace') {
            // Linux shell inside container
            sh 'mvn --version'
        }
    }
}