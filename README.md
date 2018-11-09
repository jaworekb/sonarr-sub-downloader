# sonarr-sub-downloader-docker-qnapi
Docker image with sonarr and qnapi subtitle downloader.
# Summary
This repository is combination of [linuxserver/sonarr](https://hub.docker.com/r/linuxserver/sonarr/) docker image and [ebergama/sonarr-sub-downloader](https://github.com/ebergama/sonarr-sub-downloader) subtitle downloader script. With one change subliminal subtitle downloder is replaced by qnapi.
# Installation
1. Run docker container
2. Configure sonarr as it is described [here](https://github.com/ebergama/sonarr-sub-downloader#how-to-setup-the-script-in-sonarr). Set path `/app/sub-downloader.sh`