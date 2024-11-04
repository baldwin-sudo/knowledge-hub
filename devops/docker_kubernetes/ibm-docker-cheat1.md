# Docker CLI Cheat Sheet

| Command                                              | Description                                                  |
| ---------------------------------------------------- | ------------------------------------------------------------ |
| `curl localhost`                                     | Pings the application.                                       |
| `docker build`                                       | Builds an image from a Dockerfile.                           |
| `docker build . -t <tag>`                            | Builds the image and tags it with a specified tag.           |
| `docker CLI`                                         | Starts the Docker command line interface.                    |
| `docker container rm <container>`                    | Removes a specific container.                                |
| `docker images`                                      | Lists all images in the local Docker environment.            |
| `docker ps`                                          | Lists currently running containers.                          |
| `docker ps -a`                                       | Lists all containers, including those that exited.           |
| `docker pull <image>`                                | Pulls the latest image or repository from a registry.        |
| `docker push <image>`                                | Pushes an image or repository to a registry.                 |
| `docker run <image>`                                 | Runs a command in a new container.                           |
| `docker run -p <host-port>:<container-port> <image>` | Runs the container with published ports.                     |
| `docker stop <container>`                            | Stops a running container.                                   |
| `docker stop $(docker ps -q)`                        | Stops all running containers.                                |
| `docker tag <source> <target>`                       | Creates a tag for an image to reference it by another name.  |
| `docker –version`                                    | Displays the version of Docker CLI.                          |
| `exit`                                               | Closes the terminal session.                                 |
| `export MY_NAMESPACE=<namespace>`                    | Exports a namespace as an environment variable.              |
| `git clone <repo>`                                   | Clones the specified Git repository containing necessary artifacts. |
| `ibmcloud cr images`                                 | Lists images in the IBM Cloud Container Registry.            |
| `ibmcloud cr login`                                  | Logs your local Docker daemon into IBM Cloud Container Registry. |
| `ibmcloud cr namespaces`                             | Views namespaces you have access to within IBM Cloud.        |
| `ibmcloud cr region-set <region>`                    | Sets the target region for your cloud account.               |
| `ibmcloud target`                                    | Displays information about the targeted account.             |
| `ibmcloud version`                                   | Shows the version of IBM Cloud CLI installed.                |
| `ls`                                                 | Lists the contents of the current directory to view artifacts. |