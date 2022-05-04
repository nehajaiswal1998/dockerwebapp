node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/', 'dockerhub') {

        def customImage = docker.build("nehajaiswal1998/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
