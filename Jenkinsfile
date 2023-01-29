node {

    checkout scm

    docker.withRegistry('http://hub.docker.com', 'pratheeknk1205-dockerhub') {

        def customImage = docker.build("pratheeknk1205/pratheeknk1205")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
