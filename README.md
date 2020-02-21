# Public Talks

## Securing Untrusted Workloads with Kata Containers on Kubernetes

Whilst containers have allowed for quick and easy deployment and execution of workloads, they come with their drawbacks in terms of security and isolation. This is evident when running untrusted workloads, where isolation and separation of customer workloads is paramount in a multi-tenanted environment.

With years of experience running the Bitbucket Pipelines infrastructure, Atlassian engineers David Angot and Alex Price will explore the challenges faced, such as kernel vulnerabilities, providing access to Docker in Docker (DinD) and “privileged” containers when managing a platform that executes untrusted code.

With security in mind, they will explore Kata Containers, a runtime for Containerd and CRI-O that provisions Kubernetes pods as Virtual Machines, each with their own kernel and resources and most importantly isolation.

- **David Angot & Alex Price, Atlassian**
- **Thursday, December 12 2019, Kubernetes Forum, Sydney**
- **Video: https://www.youtube.com/watch?v=hDHfRiUGVQo**
- **Slides: [Securing Untrusted Workloads with Kata Containers on Kubernetes.pdf](./slides/Securing%20Untrusted%20Workloads%20with%20Kata%20Containers%20on%20Kubernetes.pdf)**
