<p align="center">
<img src="Docker/Docker1.svg" width="700">
</p>

<br/>
<br/>
<br/>

**Docker is an open platform for developing, shipping, and running applications.**

docker is a platform which packages and application and all its dependencies together in the form of container.

- **Docker File :** Docker file is a text document containing all the commands the user requires to call on the command line to assemble an image.

- **Docker Images :**  Template to create docker container.

- **Docker Containers :** Running instance of the docker image. Container hold entire package to run the application.
<p align="center">
<img src="Docker/0_CP98BIIBgMG2K3u5.png" width="500">
</p>

- <a href="https://hub.docker.com/"> Docker Hub </a>

<br>
Check the version

```powershell
docker -v
```
<br>
Pull image

```powershell
docker pull [ImageName]
```

<br>
Pull image with version

```powershell
docker pull [ImageName]:version
```

<br>
See all the images

```powershell
docker images
```

<br>
See all the images

```powershell
docker images
```

<br>
Search images

```powershell
docker search [ImageName]
```

<br>
Run an image 

```powershell
docker run [ImageName]
docker run [ImageID]
```

<br>

Show the created container
```powershell
docker ps -a
```

<br>

Run at detached mode or create container and run
```powershell
docker run -d [ImageName]
docker run --name [ContainerName] -d [ImageName]/[ImageID]
```

<br>

Run image at backgroud 
```powershell
docker run --name [ContainerName] -it -d [ImageName]/[ImageID]
```

