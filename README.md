# note
there is transport point for gcr.io or other
but just a litter debug need to fix, it download the same image not two difficult images when use the one github-auto-build repository
the url about is that https://scanner.heptio.com/f32cf4c520c5ce2cbece684119d8ff2c/
#
kubectl apply -f https://scanner.heptio.com/f32cf4c520c5ce2cbece684119d8ff2c/yaml/
# images-list
gcr.io/heptio-images/sonobuoy:v0.13

gcr.io/heptio-images/kube-conformance:latest

gcr.io/heptio-images/scanner-forwarder:v0.0.4

gcr.io/heptio-images/namespace-deleter:v0.0.1
# kubernetes-images-list
k8s.gcr.io/kube-apiserver:v1.14.3

k8s.gcr.io/kube-controller-manager:v1.14.3

k8s.gcr.io/kube-scheduler:v1.14.3

k8s.gcr.io/kube-proxy:v1.14.3

k8s.gcr.io/pause:3.1

k8s.gcr.io/etcd:3.3.10

k8s.gcr.io/coredns:1.3.1
# latest
the useful images is in 192.168.55.103 docker images and persion-docker.io
