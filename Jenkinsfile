node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhublogin') {

        def customImage = docker.build("nehajaiswal1998/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
