# quickstart
Get started with ML Architecture at Scale by familiarizing yourself with some foundational concepts.


---
# Technical Background

- [The Essence of Linear Algebra (3B1B) (PLAYLIST)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

- [The Essence of Calculus (3B1B) (PLAYLIST)](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)

- [Neural Network Basics (3B1B) (PLAYLIST)](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

- [Learning Math for ML (YC) (ESSAY)](https://www.ycombinator.com/library/51-learning-math-for-machine-learning)
- [How to Read Mathematics (ESSAY)](http://www.people.vcu.edu/~dcranston/490/handouts/math-read.html)

- [Computational Numerical Linear Algebra (COURSE)](http://www.fast.ai/2017/07/17/num-lin-alg/)

- [Stanford CS229 Machine Learning (COURSE)](http://cs229.stanford.edu/syllabus.html#opt)


---
# Software Development

## git 

- [How to use Git and Github (2021) (Fireship.io) (VIDEO)](https://www.youtube.com/watch?v=HkdAHXoRtos)

- [Git & Github for Beginners (FreeCodeCamp) (VIDEO)](https://www.youtube.com/watch?v=RGOj5yH7evk)

- [13 Advanced Git Tips and Tricks (Fireship.io) (VIDEO)](https://www.youtube.com/watch?v=ecK3EnyGD8o)

- [Interactive Game to Learn Git Branching (WEB APP)](https://learngitbranching.js.org/?locale=en_US)

- [Another Game for Git (Desktop App)](https://ohmygit.org/)

## python

_NOTE: Do not hesitate to change playback speed on youtube to suit your needs._

- [The Python Program Incantation: "if name main" (MCoding) (VIDEO)](https://www.youtube.com/watch?v=g_wlZ9IhbTs)

- [Features: F-Strings (MCoding) (VIDEO)](https://www.youtube.com/watch?v=BxUxX1Ku1EQ)

- [Classes: `staticmethod` vs `classmethod` (MCoding) (VIDEO)](https://www.youtube.com/watch?v=SXApHXsDe8I)

- [Classes: The Difference between `__init__` and `__new__` (MCoding) (VIDEO)](https://www.youtube.com/watch?v=-zsV0_QrfTw)

- [Classes: Dataclasses and when to use them (MCoding) (VIDEO)](https://www.youtube.com/watch?v=vBH6GRJ1REM)

- [Classes: Dataclass Alternatives (MCoding) (VIDEO)](https://www.youtube.com/watch?v=vCLetdhswMg)

- [Optimizations: Caching Lookups (MCoding) (VIDEO)](https://www.youtube.com/watch?v=DnKxKFXB4NQ)

- [Optimizations: Cache and Branch-Predictability (MCoding) (VIDEO)](https://www.youtube.com/watch?v=EmzdmqUWq3o)

- [Features: New In Python 3.10 (MCoding) (PLAYLIST)](https://www.youtube.com/playlist?list=PLJ_usHaf3fgOp9XxbwVNkbyp1g72QQI6m)

- [Classes: Factory Pattern, Plugin Architecture (ArjanCodes) (VIDEO)](https://www.youtube.com/watch?v=iCE1bDoit9Q)

- [Optimizations: Removing "code smell" / bad practices (ArjanCodes) (VIDEO)](https://www.youtube.com/watch?v=LrtnLEkOwFE)

- [Features: Decorators (Kite) (VIDEO)](https://www.youtube.com/watch?v=r7Dtus7N4pI)

- [Optimizations: Speed up slow code: `async` / `await` (MCoding) (VIDEO)](https://www.youtube.com/watch?v=m_a0fN48Alw)

- [Optimizations: Looping in Python (MCoding) (VIDEO)](https://www.youtube.com/watch?v=Qgevy75co8c)


## GNU/Linux Tooling
- mention a "core set" (`cat`, `find`, `sed`, `grep`, `awk`, `tee`)
- TODO: compile a couple "awesome lists"
- To avoid freezing when RAM is low, see [Adding swap space](https://linuxize.com/post/how-to-add-swap-space-on-ubuntu-20-04/)

## Operating Systems
- not going to talk much about this ... just some things to keep in mind
- be prepared to work and deploy things on various operating systems
- Debian-based distributions like Ubuntu are very commonly chosen for deploying microservices
- some are lightweight and security focused (e.g. Alpine), others meant for enterprise-level stability (e.g. CentOS)
- using containers for development can allow you to match the runtime environment of your production code
- the more comfortable you are working across different operating systems, the easier time you will have when thrown into unfamiliar environments

---
# Operationalization
_Taking your prototypes to production._

## container technologies
### docker, containerd, podman
- [Rootless Docker Containers](https://medium.com/redbubble/running-a-docker-container-as-a-non-root-user-7d2e00f8ee15)

### kubernetes

## data access
- [Overview of Databases (ARTICLE)](https://www.jamesserra.com/archive/2015/08/relational-databases-vs-non-relational-databases/)

TODO: fill in some helpful links on topics below
### relational
- postgres, mariadb, mysql, find something that discusses all these and link to it here.
- basic principles of querying
- star schema, normalization
- proprietary (snowflake, dynamo)

### non-relational
- object storage (s3)
- names of technologies for this (mongo)

- hot storage
  - _expensive storage, cheap access_
  - AWS, GCP, what are they called in these platforms?
  - [10 Things You Might Not Know About S3 (ARTICLE)](https://www.sumologic.com/insight/10-things-might-not-know-using-s3/)

- cold storage
  - _cheaper storage, more expensive access_

- warm storage
  - _middle ground between hot and cold_

- provisioned vs elastic storage
  - filesystem and OS has to live somewhere, usually SSD hardware, fast IO, no bandwidth required internally to access storage. Very expensive to scale this. usually provisioned as part of the class of compute, you get what you get at that price point and your app better deal with it.
  - can mount other storage types to your compute instance with separate pricing model and features like snapshotting, pre-allocated storage that you can scale as you need to (e.g. EBS)
  - (unadvised) can mount s3 storage as a filesystem
  - there may exist options that only make you pay for what you use, but at a higher rate (e.g. EFS on AWS, an elastic file storage service)

## microservices architecture
- [Martin Fowler](https://www.martinfowler.com/articles/microservices.html)
- [Wikipedia](https://en.wikipedia.org/wiki/Service-oriented_architecture)

## cloud providors

### auto-scaling
- GCP: "Cloud Run"
- AWS: "Elastic Beanstalk"
- Azure: 

### VM instances
- AWS: EC2
- GCP: Compute Engine
- Azure: 

### infrastructure as code
- cross platform: Terraform
- AWS: Cloud Formation
- GCP: Cloud Build [IaC](https://cloud.google.com/recommender/docs/tutorial-iac)
- Azure: Azure Resource Manager [IaC](https://docs.microsoft.com/en-us/devops/deliver/what-is-infrastructure-as-code)


## ml lifecycle
[Martin Fowler's Article on Continuous Delivery for ML](https://martinfowler.com/articles/cd4ml.html)

### training
- [Martin Fowler](https://martinfowler.com/articles/cd4ml.html#ReproducibleModelTraining)


### tracking
- [Martin Fowler](https://martinfowler.com/articles/cd4ml.html#ExperimentsTracking)
- [MLFlow with Docker-Compose](https://github.com/ml-starter-packs/mlflow-docker-compose)

### testing
- pytest, unit test
- [Types of Testing (Atlassian) (ARTICLE)](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)
