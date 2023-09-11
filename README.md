# Docker command alias

The alias for the docker.

## Install

Choose the version you want to use. `docker-sudo.zsh` will execute the docker with `sudo` while `docker.zsh` won't.

- **oh-my-zsh**: Copy the file to `~/.oh-my-zsh/custom`.
- **zsh**: Copy the content to `~/.zshrc`.
- **bash**: Copy the content to `~/.bashrc`.
- **Other shell**: Copy the content to the shell's profile.

## Usage


|alias|command|
|---|---|
|`dk`|`docker`|
|`dkc`|`docker container`|
|`dkcls`|`docker container ls`|
|`dkcla`|`docker container ls -a`|
|`dkcrm`|`docker container rm`|
|`dkccl`|`docker container rm -f $(docker ps -aq)`|
|`dkckl`|`docker container kill`|
|`dki`|`docker image`|
|`dkis`|`docker images`|
|`dkils`|`docker image ls`|
|`dkirm`|`docker image rm`|
|`dkr`|`docker run`|
|`dkrd`|`docker run -d`|
|`dkrit`|`docker run -it`|
|`dke`|`docker exec`|
|`dkeit`|`docker exec -it`|
|`dkv`|`docker volume`|
|`dkvls`|`docker volume ls`|
|`dkins`|`docker inspect`|
|`dkl`|`docker logs`|
|`dkt`|`docker tag`|
|`dkpl`|`docker pull`|
|`dkp`|`docker push`|
|`dkb`|`docker build`|
