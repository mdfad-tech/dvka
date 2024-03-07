# Damn Vulnerable Kubernetes Application (DVKA)

DVKA is a series of apps deployed on Kubernetes that are damn vulnerable.

The content of this repository is divided into two sections.

## Challenges

Practice your `Kubernetes` exploitation techniques by solving these fun challenges.

- [Challenge 1 - Hack The NFT Museum](./challenge-1/README.md)
- [Challenge 2 - Enterprise Grade Network Debugging Console](./challenge-2/README.md)

## Workshop

Learn everything you need to know to be proficient at `Kubernetes` security.

### Beginner

- [Create New Kubernetes Cluster Using Kind](./workshop/lab-1/README.md)
- [Explore ~/.kube/config File And Kubectl Command](./workshop/lab-2/README.md)
- [Explore k9s To Manage Your Cluster](./workshop/lab-3/README.md)
- [Deploy Kubernetes Workload](./workshop/lab-4/README.md)
- [Get a Shell to a Running Container](./workshop/lab-5/README.md)
- [ConfigMaps & Secrets](./workshop/lab-6/README.md)
- [Namespaces](./workshop/lab-7/README.md)
- [Pod Security Context](./workshop/lab-8/README.md)

### Intermediate

- Kubernetes certificate authority (Coming soon)
- `cert-manager`: X.509 certificate management for Kubernetes (Coming soon)
- [Pod Resource Limits](./workshop/lab-9/README.md)
- [Scratch Containers](./workshop/lab-10/README.md)
- Pod Security Policies (Coming soon)
- Open Policy Agent (Coming soon)
- [Service Account Token](./workshop/lab-11/README.md)
- [Network Security Policies With Calico](./workshop/lab-12/README.md)

### Advanced

- Vault K8s: Encrypted Kubernetes secrets (Coming soon)
- Pod SecComp profiles (Coming soon)
- Pod AppArmor profiles (Coming soon)
- Debug Distroless And Slim Containers (Coming soon)
- The Istio service mesh (Coming soon)
- [kube-bench: CIS Kubernetes Benchmark](./workshop/lab-13/README.md)
- [kube-hunter: Hunt for security weaknesses in Kubernetes clusters](./workshop/lab-14/README.md)
- [kube-linter: Check Kubernetes YAML files and Helm charts](./workshop/lab-15/README.md)
- [terrascan: Static code analyzer for Infrastructure as Code](./workshop/lab-16/README.md)
- [kubeaudit: Audit your Kubernetes clusters against common security controls](./workshop/lab-17/README.md)
- Deploy privileged container, A Container That Doesn't Contain Anything (Coming soon)
- Container escape (Coming soon)
- Container Runtime Exploit `CVE-2019-5736` (Coming soon)
- Kubernetes misconfiguration (Coming soon)

## Tools Used During The Workshop

The provided **virtual machine** contains everything you need to go over the labs:

[🚀 download link 🔗](https://drive.google.com/file/d/12IX4xGvfqgZLrtutimWqQdxpJRRzDPto/view)

> 🔒 Credentials - **username:** kubernetes / **password:** security

![virtual machine](./workshop/images/virtual-machine.jpeg)

Alternatively, you can manually install the following tools:

- [jq](https://jqlang.github.io/jq/)
- [Docker](https://docs.docker.com/engine/install/)
- [Kind](https://kind.sigs.k8s.io/docs/user/quick-start/#installation)
- [kubectl](https://kubernetes.io/docs/tasks/tools/#kubectl)
- [Kustomize](https://kustomize.io/)
- [k9s](https://k9scli.io/topics/install/)
- [mkcert](https://github.com/FiloSottile/mkcert)
- [kube-bench](https://raw.githubusercontent.com/aquasecurity/kube-bench/main/job.yaml)
- [kube-hunter](https://github.com/aquasecurity/kube-hunter)
- [kube-linter](https://github.com/stackrox/kube-linter/releases/download/v0.6.5/kube-linter-linux.tar.gz)
- [terrascan](https://github.com/tenable/terrascan/releases/download/v1.18.3/terrascan_1.18.3_Linux_x86_64.tar.gz)
- [kubeaudit](https://github.com/Shopify/kubeaudit/releases/download/v0.22.0/kubeaudit_0.22.0_linux_amd64.tar.gz)
