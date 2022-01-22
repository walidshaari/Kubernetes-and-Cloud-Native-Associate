[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# Kubernetes-and-Cloud-Native-Associate KCNA

<p align="center">
  <img width="360" src="KCNA-logo.png">
</p>

Online curated resources that will help you prepare for taking the [Kubernetes and Cloud Native Associate **KCNA** Certification](https://training.linuxfoundation.org/certification/kubernetes-cloud-native-associate/) exam.

- Please raise an issue, or make a pull request for fixes, new additions, or updates.

## Exam Brief

- Duration : one and a half (1.5) hours
<!-- Number of questions : ??? Multiple choice questions -->
- Passing score: 75%
- Certification validity: three (3) years
- Prerequisite: None
- Cost: $250 USD, One (1) year exam eligibility, with a free retake within the year.
- General idea, What is the exam all about? and what was its objectives? [Katie Gamanji interview by TFIR/Swapnil](https://youtu.be/riUxKl95Ebs)

  *Linux Foundation offer several discounts around the year, try to check first if there is a discount. e.g. CyberMonday, Kubecon attendees among other special holidays/events*
  
## Qucik preps:
- First, a history and background
  - Cloud Natvie Computing Foundation conext from a CNCF legend Dan Kohn in less than 10 minutes [Keynote: Stitching Things Together – Dan Kohn, Executive Director, Cloud Native Computing Foundation](https://youtu.be/lmGFgZ889kY)

### Repo Strategy (My opinion on what is important)
This is a good start into cloud-native and Kubernetes journey, it won't gurantee you a [job or salary increase](https://kube.careers/report-2021-q4#:~:text=for%20Kubernetes%20jobs%3F-,Not%20much%2C%20it%20seems.,-Of%20all%20the). your goal should be to learn more about cloud-native computing foundation CNCF, and Kubernetes eco-systems and how that might help you in your career or hobbies.
- Join a cncf community, local or virtual, be part of the cncf community
- Understand and learn the basics:
  - Nana and Amigoscode created a 4 hour video covering (Docker and Kubernetes)[https://youtu.be/bhBSlnQcq2k]  
- Ensure you start early in understanding and applying best practices:
  - [Container image build best practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
  
- Get more overview of the CNCF ecosystem
  - [The CNCF Glossary](https://glossary.cncf.io/)
  - Saiyam Pathak [CNCF minutes](https://www.youtube.com/playlist?list=PL5uLNcv9SibB658blGUEv18IhcMGL0dxC)
  - Blog posts

- Understand and learn the history, differences and special use cases espically for CNCF projects
  - For example Docker vs. Containerd vs. CRI-o, and other container runtimes e.g. rkt, gvisor, kata.
  - The different Gitops engines: Flusk, ArgoCD, Fleet
- Don't stop learning and always be curious
Another opinion:  Saiyam KCNA Kubernetes and cloud native associate certification https://youtu.be/iGkFHB1kFZ0



### Cloud native definition
- Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and **declarative APIs** exemplify this approach.

- These techniques enable loosely coupled systems that are **resilient**, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.

The Cloud Native Computing Foundation seeks to drive adoption of this paradigm by fostering and sustaining an ecosystem of open source, **vendor-neutral** projects. We democratize state-of-the-art patterns to make these innovations accessible for everyone.

## KCNA curiculim repo topics overview

- [X] [Kubernetes Fundamentals - 46%](#kubernetes-fundamentals---46)
- [X] [Container Orchestration - 22%](#container-orchestration---22)
- [X] [Cloud Native Architecture - 16%](#cloud-native-architecture---16)
- [X] [Cloud Native Observability - 8%](#cloud-native-observability---8)
- [X] [Cloud Native Application Delivery - 8%](#cloud-native-application-delivery---8)

#### Extra helpful materials

- [x] [Slack](#slack)
- [x] [Books](#books)
- [x] [Youtube Videos](#youtube-videos)
- [x] [Webinars](#webinars)
- [x] [Extra Kubernetes security resources](generic-kubernetes-containers-security/Kubernetes.md)

### [Kubernetes Fundamentals](https://kubernetes.io/docs/concepts/) - 46%

1. Kubernetes Resources
2. - `kubectl api-resources`
3. - [Ivan Velichko Working with Kubernetes API](https://iximiuz.com/en/series/working-with-kubernetes-api/)
4. Kubernetes Architecture
5. Kubernetes API
6. Containers
7. [Scheduling](https://kubernetes.io/docs/concepts/scheduling-eviction/)

### Container Orchestration - 22%

1. [Container Orchestration Fundamentals](link)
2. [Runtime]
3. [Security]
4. [Networking]()
5. [Service Mesh](link)
6. [Storage](link)

### Cloud Native Architecture - 16%

1. [Autoscaling](link)
2. [Serverless](link)
3. [Community and Governance](link)
4. [Personas](link)
5. [Open Standards](link)

### Cloud Native Observability - 8%

1. [Telemetry & Observability](link)
2. [Prometheus](link)
3. [Cost Management](link)

### Cloud Native Application Delivery - 8%

1. Application Delivery Fundamentals
   - [CNCF Application Delivery Technical Advisory Group "TAG" ](https://github.com/cncf/toc/blob/1f7c705ffc9d2a3fb69ea735986f07cdcb1b008e/tags/app-delivery.md)
1. GitOps
   -  [Linux Foundation free gitops introduction course](https://training.linuxfoundation.org/training/introduction-to-gitops-lfs169/)
   -  [Codefresh free Gitops certification and course](https://codefresh.learnworlds.com/)
1. CI/CD
    -  [CNCF free CI/CD with Kuberentes book](https://www.cncf.io/free-ebook-ci-cd-with-kubernetes/)

### Slack

1. [Kubernetes Community - #kcna-exam-prep](https://kubernetes.slack.com)
1. [Kubernetes Community](https://kubernauts-slack-join.herokuapp.com/)
2. [Saiyam's Pathak OpenSource Discord](https://discord.gg/9PQBYKntPR)

### Training and practice exams:
- [UDEMY Kubernetes and Cloud Native Associate (KCNA) Practice Exams](https://www.udemy.com/course/kubernetes-and-cloud-native-associate-kcna/)
- [Linux Foundation Kubernetes and Cloud Native Essentials (LFS250)](https://training.linuxfoundation.org/training/kubernetes-and-cloud-native-essentials-lfs250/)
- [Exampro.co course and practice exams](https://www.exampro.co/)  -- in-progress, should be out first-second week of Feburary 2022, watch this space
- [VMware Kube Academy](https://kube.academy/)
- [CIVO k8s Acadmey](https://www.civo.com/academy)

### Other Repos
- [Mohamed Abukar, AWS community builder KCNA repo](https://github.com/moabukar/Kubernetes-and-Cloud-Native-Associate-KCNA)
### Youtube Videos
1. [Saim cloud-native fmpodcast Deep Dive KCNA Exam episode 31](https://youtu.be/wPbsvF_SGmc)

#### Blogs and writeups
- https://blog.bradmccoy.io/how-to-pass-your-kcna-exam-cf98cfa7d70f
- https://medium.com/@marino.wijay/the-kcna-exam-a-quick-guide-to-kicking-off-your-k8s-and-cloud-native-journey-56a3a5be345

