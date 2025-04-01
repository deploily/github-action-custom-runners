# github-action-custom-runners
Customized images for Github Actions Runner Controller

# Test build images 

```bash
docker build -t test-runner -f  ./actions-runner-ubuntu-20.04-kubectl.Dockerfile .
docker image rm test-runner
```
