##   Docker commands:

  1. Build an image:

    docker build -t image_name .

  2. List all images:

    docker images

  3. Run a container:
     
    docker run -p host_port:container_port -d --name container_name image_name

  4. List running containers:

    docker ps

  5. List all containers (including stopped ones):

    docker ps -a

  6. Stop a running container:
  
    docker stop container_name_or_id

  7. Remove a container:

    docker rm container_name_or_id

  8. Remove an image:

    docker rmi image_name_or_id

  9. View container logs:

    docker logs container_name_or_id

  10. Enter a running container (opens a shell):

    docker exec -it container_name_or_id /bin/bash

  11. Push an image to Docker Hub:

    docker push username/image_name:tag

  12.Pull an image from Docker Hub:

    docker pull username/image_name:tag

  13. Inspect a container (get detailed information):

    docker inspect container_name_or_id

  14. Inspect an image:

    docker image inspect image_name_or_id

  15. Clean up unused resources (containers, images, networks, etc.):

    docker system prune

  16. View resource usage statistics:

    docker stats

  17. Create a network:

    docker network create network_name

  18. List networks:

    docker network ls

  19. Remove a network:

    docker network rm network_name

  20. Build and run a container in one command:

    docker run -p host_port:container_port -d --name container_name image_name
