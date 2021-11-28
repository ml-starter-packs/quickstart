# quickstart
Get started with ML Architecture at Scale by familiarizing yourself with some foundational concepts.


---
# Technical Background
port examples from https://www.mathematicalmichael.com/resources/machinelearning/

- [The Essence of Linear Algebra (PLAYLIST)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
- [The Essence of Calculus (PLAYLIST)](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
- [Neural Network Basics (PLAYLIST)](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)


---
# Software Development
## python

_NOTE: Do not hesitate to change playback speed on youtube to suit your needs._

- [The Python Program Incantation: "if name main" (VIDEO)](https://www.youtube.com/watch?v=g_wlZ9IhbTs)

- [Features: F-Strings (VIDEO)](https://www.youtube.com/watch?v=BxUxX1Ku1EQ)

- [Classes: The Difference between `__init__` and `__new__` (VIDEO)](https://www.youtube.com/watch?v=-zsV0_QrfTw)

- [Classes: Dataclasses and when to use them (VIDEO)](https://www.youtube.com/watch?v=vBH6GRJ1REM)

- [Optimizations: Caching Lookups (VIDEO)](https://www.youtube.com/watch?v=DnKxKFXB4NQ)

- [Optimizations: Cache and Branch-Predictability (VIDEO)](https://www.youtube.com/watch?v=EmzdmqUWq3o)

- [Features: New In Python 3.10 (PLAYLIST)](https://www.youtube.com/playlist?list=PLJ_usHaf3fgOp9XxbwVNkbyp1g72QQI6m)

- [Classes: Factory Pattern, Plugin Architecture (VIDEO)](https://www.youtube.com/watch?v=iCE1bDoit9Q)

- [Optimizations: Removing "code smell" / bad practices (VIDEO)](https://www.youtube.com/watch?v=LrtnLEkOwFE)

- [Features: Decorators (VIDEO)](https://www.youtube.com/watch?v=r7Dtus7N4pI)

- [Optimizations: Speed up slow code: `async` / `await` (VIDEO)](https://www.youtube.com/watch?v=m_a0fN48Alw)


## GNU/Linux Tooling
- mention a "core set" (`cat`, `find`, `sed`, `grep`, `
- compile a couple "awesome lists"


## data access
### relational
- postgres, mariadb, mysql, find something that discusses all these and link to it here.
- basic principles of querying
- star schema, normalization
- proprietary (snowflake, dynamo)

### non-relational
- object storage
- names of technologies for this (mongo)


here is something that talks most of the the above: https://www.jamesserra.com/archive/2015/08/relational-databases-vs-non-relational-databases/

## 

---
# Operationalization
Taking your prototypes to production.

## container technologies
### docker, containerd, podman

### kubernetes


## object storage

### hot storage
- AWS, GCP, what are they called in these platforms?
- [10 Things You Might Not Know About S3 (ARTICLE)](https://www.sumologic.com/insight/10-things-might-not-know-using-s3/)

### warm storage

### cold storage

## microservices architecture

## cloud providors

### auto-scaling
- GCP: "Cloud Run"
- AWS: "Elastic Beanstalk"
- Azure: 

### VM instances
- AWS: EC2
- GCP: Compute Engine
- Azure: 

## infrastructure as code
- cross platform: Terraform
- AWS: Cloud Formation
- GCP: Cloud Build [IaC](https://cloud.google.com/recommender/docs/tutorial-iac)
- Azure: Azure Resource Manager [IaC](https://docs.microsoft.com/en-us/devops/deliver/what-is-infrastructure-as-code)


## ml lifecycle
[Martin Fowler's Article on Continuous Delivery for ML](https://martinfowler.com/articles/cd4ml.html)

### tracking
- [Martin Fowler](https://martinfowler.com/articles/cd4ml.html#ExperimentsTracking)
- [MLFlow with Docker-Compose](https://github.com/ml-starter-packs/mlflow-docker-compose)

### testing

