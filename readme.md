# Kubernetes Tests

Currently using the following for testing:
- minikube
- traefik

## Setup
All of these configs assume that Traefik is already running in Kubernetes. If its not, just run `kubectl apply -f ./traefik-deployment.yml`.

For the `chrismarslender.dev` site (Hello World), run `kubectl apply -f ./chris-deployment.yml`

You'll also need to make sure the following domains are added to your hosts file, at the IP that is returned from `minikube ip`:
- chrismarslender.dev
- traefik-ui.dev

