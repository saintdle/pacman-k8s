# pacman-k8s

This is a simple pacman app that utilizes the default storage class in Kubernetes for storing high score using MongoDB. Web UI Exposed by LoadBalancer.

```
git clone https://github.com/saintdle/pacman-k8s
cd pacman-k8s
oc create -f .
kubectl get svc -n pacman
```
Play pacman in your web browser on the IP address specified by the Load Balancer service
Original code from >>> https://github.com/dav1x/pacman-ocp
