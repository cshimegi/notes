# **Udemy: Learn Hands-on Containerization and Orchestration with Docker Ecosystem (Docker, Compose and Swarm)**
<br>

# Road map
```mermaid
graph LR
    id1[Docker & Dockerfile] --> id2[Images & Containers] --> id3[Networking] --> id4[Storage] --> id5[Docker Compose] --> id6[Swarm Mode]
```
# Concept
- ### Up to ***application layer***
- ### Flow
```mermaid
graph LR
    id1[Dockerfile => Build] --> id2[Docker Image => Ship] --> id3[Containers => Run]
```
- ### Docker Architechture
  - Client: a machine which we use to interact with Docker
    1. via CLI
    2. via API
  - Host: a machine which actually performs tasks of containerization
    - Run docker daemon which listens to and performs actions asked by Docker Client
    - Docker daemon builds Dockfile and turns it into docker image
  - Registry:
    - Serve as a place to store docker images and make them avaliable to others

```mermaid
graph LR
    id1[Docker Client] -->|API calls| id2[Docker Host]
    id2 -->|Results| id1

    id2 -->|Push images| id3[Docker Registry]
    id3 -->|Pull images| id2
```
- ### Docker daemon
  - Manage Docker images
  - Start and stop containers

# Docker & Dockerfile
### Dockerfile
- Sequent set

# Images & Containers
- Each layer apart from the top one is R/O
- The top layer is R/W
- Recognized by name or image ID
- Layers
  - CMD
  - Expose
  - Workdir
  - Run
  - Base image
  - bootfs

# Networking

# Storage

# Docker Compose

# Swarm Mode