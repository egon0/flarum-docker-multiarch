basically a build of https://github.com/mondediefr/docker-flarum for multiple architectures (amd64, arm64 and arm32)

to automatically build it via gitlab ci you need 3 CI vars:

 * BUILD_PLATFORMS with for example linux/amd64,linux/arm64,linux/arm/v7
 * DOCKER_LOGIN aka your Docker Hub username
 * DOCKER_PASSWORD - your Docker Hub Password
