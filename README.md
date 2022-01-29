# CapRover-Deploy

!!! Please do note that this github action was made keeping in mind that your repo is public or you don't mind others seeing your Docker Images of your Private Repos.
If you do want to modify it for Private Repos then do read: https://caprover.com/docs/ci-cd-integration.html#app-tokens

TL;DR: No TL;DR bruh. Go read it!

Pre-requisties:

Create an app in CapRover Dashboard `your-app`

Make sure your app has a Dockerfile

Add these ENV Vars as shown in your Github Repo Secrets:
```
DOCKER_HUB_USER=docker-hub-username
DOCKER_HUB_TOKEN=Your-Docker-Hub-Token
CAPROVER_URL=https://captain.root.yourdomain.com
CAPROVER_APP=your-app
CAPROVER_APP_TOKEN=your-app-token
```