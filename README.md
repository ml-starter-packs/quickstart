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

- [Advanced: Exceptions, Logging, Multiprocessing, Iterators, and more! (see description for timestamps) (VIDEO)](https://www.youtube.com/watch?v=tdn9_MZ0lN4)


## GNU/Linux Tooling
- mention a "core set" (`cat`, `find`, `sed`, `grep`, `
- compile a couple "awesome lists"

---
# Operationalization
Taking your prototypes to production.



here is something that talks most of the the above: https://www.jamesserra.com/archive/2015/08/relational-databases-vs-non-relational-databases/

## container technologies
### docker, containerd, podman

### kubernetes

## data access
### relational
- postgres, mariadb, mysql, find something that discusses all these and link to it here.
- basic principles of querying
- star schema, normalization
- proprietary (snowflake, dynamo)

### non-relational
- object storage (s3)
- names of technologies for this (mongo)

### hot storage
- AWS, GCP, what are they called in these platforms?
- [10 Things You Might Not Know About S3 (ARTICLE)](https://www.sumologic.com/insight/10-things-might-not-know-using-s3/)

### warm storage

### cold storage


## microservices architecture
- Link to fowler here

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
- 

### tracking
- [Martin Fowler](https://martinfowler.com/articles/cd4ml.html#ExperimentsTracking)
- [MLFlow with Docker-Compose](https://github.com/ml-starter-packs/mlflow-docker-compose)

### testing

