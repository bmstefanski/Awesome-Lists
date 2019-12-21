[![返回目录](https://user-images.githubusercontent.com/5803001/38079637-ff0abcf0-3371-11e8-9b76-ad651620afc7.jpg)](https://github.com/wx-chevalier/Awesome-Lists)

# Cloud OpenSource List

# Virtualization

- [LightVM #Project#](http://cnp.neclab.eu/projects/lightvm/): . With LightVM we examine whether there is indeed a strict tradeoff between isolation (VMs) and efficiency (containers). We find that VMs can be as nimble as containers, as long as they are small and the toolstack is fast enough.

- [TinyVM #Project#](https://github.com/jakogut/tinyvm): TinyVM is a virtual machine with the goal of having a small footprint. Low memory usage, a small amount of code, and a small binary.

- [gVisor #Project#](https://github.com/google/gvisor): gVisor is a user-space kernel, written in Go, that implements a substantial portion of the Linux system surface.

- [Kata Containers #Project#](https://katacontainers.io/): Kata Containers is a new open source project building extremely lightweight virtual machines that seamlessly plug into the containers ecosystem.

- [Hyper Container #Project#](https://hypercontainer.io/): Hypervisor-agnostic Docker Runtime.

# Docker

## Tool

- [ctop #Project#](https://github.com/bcicen/ctop): Top-like interface for container metrics

- [container-diff #Project#](https://github.com/GoogleCloudPlatform/container-diff): container-diff is a tool for analyzing and comparing container images. container-diff can examine images along several different criteria

- [dive #Project#](https://github.com/wagoodman/dive): A tool for exploring each layer in a docker image.

- [2019-docker-slim #Project#](https://github.com/docker-slim/docker-slim): DockerSlim (docker-slim): Don't change anything in your Docker container image and minify it by up to 30x (and for compiled languages even more) making it secure too! (free and open source)

## Storage | 存储

- [2015-Flocker #Project#](https://github.com/ClusterHQ/flocker): Flocker is an open-source Container Data Volume Manager for your Dockerized applications.

- [2017-REX-Ray #Project#](https://github.com/thecodeteam/rexray): REX-Ray is a container storage orchestration engine enabling persistence for cloud native workloads

- [GlusterFS #Project#](https://github.com/gluster/glusterfs): Gluster is a software defined distributed storage that can scale to several petabytes. It provides interfaces for object, block and file storage.

## Registry

- [Dragonfly #Project#](https://github.com/alibaba/Dragonfly): Dragonfly is an intelligent P2P based file distribution system. It aims to resolve issues related to low-efficiency, low-success rate and waste of network bandwidth in file transferring process.

- [Harbor #Project#](https://goharbor.io/): Harbor is an open source container image registry that secures images with role-based access control, scans images for vulnerabilities, and signs images as trusted.

# Kubernetes

## Management

- [krew #Project#](https://github.com/GoogleContainerTools/krew): krew is the package manager for kubectl plugins.

- [Wayne #Project#](https://github.com/Qihoo360/wayne): Web UI for Kubernetes multi-clusters

- [kubectx #Project#](https://github.com/ahmetb/kubectx): Switch faster between clusters and namespaces in kubectl

## Application Management

- [2019-kruise #Project#](https://github.com/openkruise/kruise): Automate application workloads management on Kubernetes

- [Kubernetes Helm #Project#](https://github.com/kubernetes/helm): Helm is a tool for managing Kubernetes charts. Charts are packages of pre-configured Kubernetes resources.

- [Draft #Project#](https://github.com/Azure/draft): A tool for developers to create cloud-native applications on Kubernetes.

- [Gatekeeper #Project#](https://github.com/open-policy-agent/gatekeeper): Gatekeeper - Policy Controller for Kubernetes -

## Plugins

- [OpenEBS](https://www.openebs.io/): OpenEBS is an open source storage platform that provides persistent and containerized block storage for DevOps and container environments.

## Development

- [Skaffold #Project#](https://github.com/GoogleCloudPlatform/skaffold): Skaffold is a command line tool that facilitates continuous development for Kubernetes applications.

- [Brigade #Project#](https://github.com/Azure/brigade): Script simple and complex workflows using JavaScript. Chain together containers, running them in parallel or serially. Fire scripts based on times, GitHub events, Docker pushes, or any other trigger. Brigade is the tool for creating pipelines for Kubernetes.

# Service Mesh

- [Istio #Project#](https://istio.io/about/intro.html): Istio is an open platform that provides a uniform way to connect, manage, and secure microservices. Istio supports managing traffic flows between microservices, enforcing access policies, and aggregating telemetry data, all without requiring changes to the microservice code.

- [Service Fabric #Project#](https://github.com/Microsoft/service-fabric): Service Fabric is a distributed systems platform for packaging, deploying, and managing stateless and stateful distributed applications and containers at large scale.

## Sidecar

- [Envoy #Project#](https://www.envoyproxy.io/): Envoy is an OpenSource Egde and Service Proxy, Design for Cloud-Native Applications.

- [2019-Kuma #Project#](https://kuma.io/docs/0.1.0/#what-is-kuma): Kuma is a universal open-source control plane for Service Mesh and Microservices.

# Serverless

- [2017-faas #Project#](https://github.com/alexellis/faas): Functions as a Service - a serverless framework for Docker & Kubernetes

- [1Backend #Project#](https://github.com/1backend/1backend): Run your web apps with the ease of git repos. Build reusable microservices and functions.

- [OpenWhisk #Project#](https://github.com/apache/incubator-openwhisk): OpenWhisk is a cloud-first distributed event-based programming service. It provides a programming model to upload event handlers to a cloud service, and register the handlers to respond to various events.
