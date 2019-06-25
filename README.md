# Test for Docker file permissions

A suite of test cases to investigate whether Linux file permissions under Docker & [Skaffold](https://skaffold.dev/) are preserved when the images are built on Windows hosts.


## Build with Docker Engine

```
% docker build -t test-docker src

% docker run -it test-docker
```


## Build with Skaffold

```
% skaffold build

% docker run -it test-skaffold
```


