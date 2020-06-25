# Setup GameBase locally
1. `git clone https://gitlab.tandashi.de/GameBase/setup.git`
2. `cd setup/`
2. Locate the `.kube/config` for your target Kubernetes Cluster
3. `export MY_KUBECONFIG_PATH=/path/to/.kube/config` or modify the `docker-compose.yml`
3. `docker-compose up -d`
5. Go to the [management interface](http://localhost:8080)