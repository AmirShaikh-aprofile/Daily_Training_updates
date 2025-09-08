## By mistake refreshed the page without saving, below are some command history that i have pratices
docker ps
    2  docker run hello world
    3  docker run hello-world
    4  docker ps
    5  docker images
    6  docker run helo-world
    7  docker run nginx
    8  docker ps -a
    9  docker run timer
   10  docker ps
   11  docker images
   12  docker -d nginx -p 80:80
   13  docker run -d -p 80:80 nginx
   14  docker ps
   15  docker stop 44736bb96c95
   16  docker run -d -p 8080:8080 nginx
   17  docker ps
   18  curl http://localhost:8080
   19  curl http://localhost:80
   20  curl http://localhost:8080
   21  docker run -d -p 80:80 nginx
   22  docker ps
   23  history
   24  docker volume l
   25  docker volume ls -a
   26  docker volume create jenkins_home
   27  docker run -d --name jenkins   -p 8080:8080 -p 50000:50000   -v jenkins_home:/var/jenkins_home   jenkins/jenkins:lts
   28  docker ps
   29  docker rm c3a 01f
   30  docker stop c3a 01f
   31  docker run -d --name jenkins   -p 8080:8080 -p 50000:50000   -v jenkins_home:/var/jenkins_home   jenkins/jenkins:lts
   32  docks ps
   33  docker ps
   34  docker ps -a
   35  docker purse
   36  docker rm -f
   37  docker prune
   38  docker container prune
   39  docker images prune
   40  docker image prune
   41  docker run -d --name jenkins   -p 8080:8080 -p 50000:50000   -v jenkins_home:/var/jenkins_home   jenkins/jenkins:lts
   42  docker volume ls
   43  docker ps
   44  docker version
   45  docker images
   46  docker pull tomcat:jre21-temurin-noble
   47  docker ps
   48  docker ps -a
   49  docker pull tomcat:jre21-temurin-noble
   50  docks ps
   51  docker ps
   52  docker ps -a
   53  docker rm ffb5c433e259
   54  docker ps -a
   55  docker ps
   56  docker ps -a
   57  docker images
   58  docker ps
   59  docker run tomcat
   60  docker images
   61  docker run -d -p 54a99e1aa6f1
   62  docker run -d 54a99e1aa6f1
   63  docker ps
   64  docker stop 4af75db5f233
   65  docker ps
   66  docker ps -a
   67  docker start 4af75db5f233
   68  docker ps -a
   69  docker restart 4af75db5f233
   70  docker ps -a
   71  docker rm 4af75db5f233
   72  docker stop 4af75db5f233
   73  docker rm 4af75db5f233
   74  docker ps -a
   75  docker logs 67a54edc532a
   76  docker exec -it 67a54edc532a bash
   77  ls
   78  docker ps -a
   79  docker network ls
   80  docker network testnetwork
   81  docker network create testnetwork
   82  docker network ls
   83  docker network inspect 562061dd8382
   84  docker network 562061dd8382
   85  docker network rm 562061dd8382
   86  docker network ls
   87  docker volumn ls
   88  docker volume ls
   89  docker ls
   90  docker ps
   91  docker create volume testvolume
   92  docker volume create testvolume
   93  docker volume ls
   94  docker rm testvolume
   95  docker volume inspect testvolume
   96  docker volume create volume2
   97  docker volume ps
   98  docker volume ls
   99  docker volume inspect testvolume
  100  docker volume create volume3
  101  docker volume ls
  102  docker volume rm volume3
  103  docker volume ls
  104  docks images
  105  docker images
  106  docker pull python:3.9.23-trixie
  107  docker images
  108  docker run python sleep 10
  109  docker run python:3.9.23-trixie sleep 10
  110  docker images
  111  docker run -p 5000:80 voting-app
  112  docker run -d -p 5000:80 voting-app
  113  docker ps
  114  docker run -d --name-redis redis
  115  docker ps
  116  docker run -p 5000:80 --link redis:redis voting-app
  117  history
    1  sudo install docker
    2  sudo apt install docker
    3  sudo apt-get install docker
    4  sudo update
    5  sudo apt update
    6  sudo apt install docker
    7  for pkg in docker.io docker-doc docker-compose docker-compose-v2 podman-docker containerd runc; do sudo apt-get remove $pkg; done
    8  # Add Docker's official GPG key:
    9  sudo apt-get update
   10  sudo apt-get install ca-certificates curl
   11  sudo install -m 0755 -d /etc/apt/keyrings
   12  sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
   13  sudo chmod a+r /etc/apt/keyrings/docker.asc
   14  # Add the repository to Apt sources:
   15  echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
   16    $(. /etc/os-release && echo "${UBUNTU_CODENAME:-$VERSION_CODENAME}") stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
   17  sudo apt-get update
   18  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
   19  docker --version
   20  docker ps
   21  sudo su
   22  sudo su
   23  ls
   24  mkdir git
   25  cd gi
   26  cd git/
   27  clone https://github.com/dockersamples/example-voting-app.git
   28  git clone https://github.com/dockersamples/example-voting-app.git
   29  ls
   30  cd example-voting-app/
   31  ls
   32  cd vote/
   33  ls
   34  docker build . -t voting-app
   35  sudo docker build . -t voting-app
   36  docker images
   37  sudo us
   38  sudo su
   39  history

___
## continuing the pratice for vote-app section.

- Cloned the git repo
- Builed docker image and run on port 5000
<img width="1142" height="76" alt="image" src="https://github.com/user-attachments/assets/daf61981-9055-48bb-9b46-d5610c62baa8" />
<img width="1656" height="510" alt="image" src="https://github.com/user-attachments/assets/76c76f4f-05ea-4957-a4b9-067165a6df7c" />
<img width="1671" height="560" alt="image" src="https://github.com/user-attachments/assets/8e2983c3-7b47-4d5c-bda9-468cfa0ec9a7" />

- Created redis container and linked it with vpoting-app
<img width="1238" height="357" alt="image" src="https://github.com/user-attachments/assets/424efdab-5c2e-4163-8582-4f23c1f0b243" />
<img width="1917" height="409" alt="image" src="https://github.com/user-attachments/assets/044c6f33-0c45-4db4-b88c-537972a8f6bf" />




___

##Comamnds for docker

| #  | Command                                 | Description                                              |
| -- | --------------------------------------- | -------------------------------------------------------- |
| 1  | `docker --version`                      | Displays the installed Docker version.                   |
| 2  | `docker info`                           | Shows detailed information about Docker’s environment.   |
| 3  | `docker ps`                             | Lists all running containers.                            |
| 4  | `docker ps -a`                          | Lists all containers, including stopped ones.            |
| 5  | `docker run [options] <image>`          | Creates and starts a container from an image.            |
| 6  | `docker start <container>`              | Starts a stopped container.                              |
| 7  | `docker stop <container>`               | Stops a running container.                               |
| 8  | `docker restart <container>`            | Restarts a container.                                    |
| 9  | `docker rm <container>`                 | Removes a container.                                     |
| 10 | `docker logs <container>`               | Displays logs from a container.                          |
| 11 | `docker exec -it <container> <command>` | Runs a command inside a running container interactively. |
| 12 | `docker inspect <container>`            | Shows detailed info about a container’s settings.        |
| 13 | `docker images`                         | Lists all local Docker images.                           |
| 14 | `docker pull <image>`                   | Downloads an image from a registry.                      |
| 15 | `docker build -t <name>:<tag> <path>`   | Builds an image from a Dockerfile at the specified path. |
| 16 | `docker rmi <image>`                    | Removes one or more images.                              |
| 17 | `docker tag <image> <new-image-name>`   | Assigns a new tag to an image.                           |
| 18 | `docker volume create <name>`           | Creates a new volume for persistent storage.             |
| 19 | `docker volume ls`                      | Lists all volumes.                                       |
| 20 | `docker volume inspect <volume>`        | Shows details about a volume.                            |
| 21 | `docker volume rm <volume>`             | Deletes a volume.                                        |
| 22 | `docker network create <name>`          | Creates a new network.                                   |
| 23 | `docker network ls`                     | Lists all networks.                                      |
| 24 | `docker network inspect <network>`      | Shows details of a network.                              |
| 25 | `docker network rm <network>`           | Removes a network.                                       |
| 26 | `docker system prune`                   | Cleans up stopped containers, unused net                 |

