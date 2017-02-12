# croc-hunter

Forked from github.com/lachie83/croc-hunter


# Deploy using Deis Workflow
## Dockerfile
Add Dockerfile to your repo
```
cd <repo-path>
deis create
git push deis master
```
## Docker images
```
deis create --no-remote
deis pull <repo>/<image-name> -a <app-name>
```
