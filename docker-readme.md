# docker-labs

A hands-on Docker learning repo built while preparing for DevOps interviews.
Each folder covers one concept — from basics to CI/CD integration with AWS ECR.

## Structure

| Folder | Topic |
|--------|-------|
| [01-basics](./01-basics/) | Containers, images, core CLI commands |
| [02-images](./02-images/) | Writing Dockerfiles, layers, build cache |
| [03-volumes](./03-volumes/) | Bind mounts, named volumes, data persistence |
| [04-networking](./04-networking/) | Bridge, host, DNS between containers |
| [05-compose](./05-compose/) | Multi-container apps with Docker Compose |
| [06-multi-stage-builds](./06-multi-stage-builds/) | Optimizing image size with multi-stage builds |
| [07-ecr-push](./07-ecr-push/) | Building and pushing images to AWS ECR |
| [08-docker-with-cicd](./08-docker-with-cicd/) | GitHub Actions workflow: build → push to ECR |

## Stack

- Docker Engine
- Docker Compose v2
- AWS CLI + ECR
- GitHub Actions

## Progress

- [x] 01 - Basics
- [ ] 02 - Images
- [ ] 03 - Volumes
- [ ] 04 - Networking
- [ ] 05 - Compose
- [ ] 06 - Multi-stage builds
- [ ] 07 - ECR push
- [ ] 08 - Docker with CI/CD
