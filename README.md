# voting-app-docker-compose
> [!NOTE]
> The code of the three applications (vote, worker, and result) are taken from [example-voting-app](https://github.com/dockersamples/example-voting-app). I only developed the docker-compose file to get hands-on experience

![Architecture diagram](images/architecture.excalidraw.png)

## Prerequisites
1. Docker and docker compose installed on the host
```shell
docker compose version
```
The output should be something like:
> Docker Compose version vX.XX.X

2. Clone this GitHub Repo
```shell
git clone https://github.com/anas1243/voting-app-docker-compose.git voting-app
```

## Manual
1. run the stack in the background
```shell
docker compose up -d
```
![docker compose up](images/Screenshot%202024-04-01%20at%204.40.09 PM.png)

![voting test](images/Screenshot%202024-04-01%20at%204.42.55 PM.png)
![result test](images/Screenshot%202024-04-01%20at%204.43.04 PM.png)