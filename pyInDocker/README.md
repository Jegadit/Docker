# 

### commands:

- cd into pyInDocker folder
- docker build -t testing . => %% docker build -t <build file> <path to files> %%

#### Now if you see the docker images avaliable, you can see a new REPOSITORY called testing.

- docker run testing

## Output
```
PS ~\docker\pyInDocker> docker images
REPOSITORY   TAG       IMAGE ID       CREATED          SIZE
testing      latest    729c35337fa8   50 seconds ago   143MB
ubuntu       latest    27941809078c   7 weeks ago      77.8MB

PS ~\docker\pyInDocker> docker run testing  
Hello World

PS ~\docker\pyInDocker> 
```


[Reference](https://youtu.be/uvTl6GefR9o)
