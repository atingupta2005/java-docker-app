node {
    // Get Artifactory server instance, defined in the Artifactory Plugin administration page.
    stage('Clone Repo') {
        git url: 'https://github.com/atingupta2005/java-docker-app.git'
    }

    stage('Docker Compose Delete') {
      sh "docker-compose down"
    }

    stage('Docker Compose Up') {
      sh "docker-compose up -d"
    }

  
}
