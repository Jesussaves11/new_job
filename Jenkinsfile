node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customimage = docker.build("miltonc/dockerwebapp")

        /* Push the container to the custom Registry */
        customimage.push()
    }
}