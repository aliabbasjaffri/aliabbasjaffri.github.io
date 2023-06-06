- Software Engineer 👷🏻‍♂️
- [Triathlon enthusiast](https://www.strava.com/athletes/27881761) 🏃🏻 🏊🏻 🚴🏻
- [Team Spotify](https://open.spotify.com/user/aliabbasjaffri) 🎶
- [LoTR-ed for life](https://www.youtube.com/watch?v=Sagg08DrO5U) 🧙🏻‍♂️

_I have worked for 4+ years in Software development, eventually finding my true calling in DevOps and MLOps after working in Android and iOS, full-stack dotnet, and mern stack web development. I can be reached via my email address, [ali.abbasjaffri@live.com](mailto:ali.abbasjaffri@live.com?subject=oh Hello There!), or via my [LinkedIn](https://www.linkedin.com/in/aliabbasjaffri) and my work can be viewed on my [github](https://github.com/aliabbasjaffri/). I recently started to pen down my thoughts on [medium](https://medium.com/@aliabbasjaffri_/) regarding different tools that i use on a daily basis, including some tutorials and how i managed to solve some interesting challenges. You can also pick up a slot on my [calendar](https://cal.com/aliabbasjaffri) to talk about anything Dev / ML Ops._

## Experience

### [union.ai](https://www.union.ai/)

**Oct 2022 &rarr; Present**

_Remote; Munich, Germany_

- Infrastructure engineer, responsible for defining strategy and implementing a multi-cloud highly scalable and reliable infrastructure for union.ai flagship product, [flyte](https://flyte.org/)
- Designed, documented, and implemented managed infrastructure for flyte on [AWS](https://aws.amazon.com/) and [GCP](https://cloud.google.com/) cloud platforms. Managed flyte is comprised of managing regional control planes and having customer dataplanes connect to it. flyte control plane manages multiple services and components including [FlyteAdmin, FlyteConsole and DataCatalogue](https://docs.flyte.org/en/latest/deployment/deployment/index.html#deployment-deployment).
- Configured and managed Kubernetes for cost-effective scalability and reliability of managed flyte for customers. This includes setting up VPC and networking layer, as well as Kubernetes Cluster and respective nodesgroups (AWS managed as well as self managed) for customer workloads. Majority of infrastructure is configured via Terraform.
- Managed and enhanced [buildkite pipelines](https://buildkite.com/) for efficient deployment of internal services and infrastructure. These pipelines are responsible for deployment of services within the union monorepo as well as union control planes and customer dataplanes.
- Automated internal processes using [pyinvoke](https://www.pyinvoke.org/) and [makefiles](https://www.gnu.org/software/make/)
- System Monitoring and Troubleshooting using [Grafana Cloud](https://grafana.com/products/cloud/) and [Grafana Agent](https://grafana.com/docs/agent/latest/)
- Participated in [OnCall](https://grafana.com/products/cloud/oncall/) rotation for round-the-clock system monitoring and prompt issue resolution
- Comprehensive and clear documentation of requirements, processes and tooling. This included tool analyses, deployment plans as well as operational manuals

### [Reply AG](https://www.linkedin.com/company/machine-learning-reply-de/)

**Nov 2020 &rarr; Sept 2022**

_Munich, Germany_

- Software engineering consultant with a focus towards ML engineering
- worked with multiple clients in Reply's portfolio, primarily on PoCs, on the following topics:
  - data and feature exploration using standard data science stack (`jupyter notebooks`, `pandas`, `numpy`, `seaborn`) and data versioning and ETL pipelines using [dvc](https://dvc.org/doc/start/data-and-model-versioning) and [Airflow](https://airflow.apache.org/)
  - provisioned and maintained machine learning platform infrastructure on [AWS](https://aws.amazon.com/) and cloud migration to [Azure](https://azure.microsoft.com/en-us/) using [terraform](https://www.terraform.io/), [terragrunt](https://terragrunt.gruntwork.io/), [pulumi](https://www.pulumi.com/) and [ansible](https://www.ansible.com/).
  - monitoring of machine learning projects in production using [Grafana](https://grafana.com/) and [Prometheus](https://prometheus.io/).
  - Created retrainable ML pipelines with terraform using multiple AWS cloud services for customer churn prediction.

### [Medikura Digital Health GmbH ( now XO Life )](https://www.linkedin.com/company/xo-life/)

**June 2019 &rarr; Aug 2020**

_Munich, Germany_

- Software Engineer with a focus towards DevOps
- worked closely with CTO in development and maintenance of Medikura's microservice and [microfrontend](https://micro-frontends.org/) oriented infrastructure.
- key areas / technologies that i contributed:
  - refactored microservices and frontends as per [12 factor app rules](https://12factor.net/)
  - set up [automated scaling of gitlab runners](https://docs.gitlab.com/runner/configuration/autoscale.html) to speed up code build and deployment tasks during peak hours
  - created gitlab pipelines for build, test and faster [code reviews](https://docs.gitlab.com/ee/development/testing_guide/review_apps.html#review-apps)
  - created [multistage docker builds](https://docs.docker.com/develop/develop-images/multistage-build/) for all micro frontends and services to make use of efficient layer caching and faster builds
  - [docker buildx](https://docs.docker.com/buildx/working-with-buildx/) to speed up docker image builds
  - management of [Rancher kubernetes](https://rancher.com/) for microservice deployment and orchestration in development, staging and production environments
  - [high availability deployment of Rancher kubernetes](https://rancher.com/docs/rancher/v2.6/en/installation/resources/k8s-tutorials/infrastructure-tutorials/infra-for-ha/) for fault tolerance
  - created [NGINX ingress](https://kubernetes.github.io/ingress-nginx/)es for exposing micro frontends and services.
  - helped set up high availability deployments of hashicorp [consul](https://www.consul.io/) for service discovery and [vault](https://www.vaultproject.io/) for [security of data](https://www.hashicorp.com/products/vault/data-protection)
  - set up automated certificate creation for web facing microfrontends using [OpenSSL](https://www.openssl.org/), [LetsEncrypt](https://letsencrypt.org/) and [certmanager](https://cert-manager.io/)
  - high availability and security of [MongoDB](https://docs.mongodb.com/manual/core/replica-set-high-availability/), [Event Store](https://developers.eventstore.com/server/v21.10/cluster.html#cluster-with-gossip-seeds) and [consul](https://learn.hashicorp.com/tutorials/vault/ha-with-consul) databases
  - development of microservices on [node.js](https://nodejs.org/en/)

### [Siemens AG](https://www.linkedin.com/company/siemens/)

**Aug 2018 &rarr; May 2019**

_Munich, Germany_

- Software Engineer with a focus towards IoT
- helped add features to the iOS [app for Siemoji](https://new.siemens.com/global/en/company/stories/research-technologies/topics/the-future-of-manufacturing-siemoji.html), which was continuation of my [iOS Praktikum course](https://ase.in.tum.de/lehrstuhl_1/teaching/older-terms/121-teaching/st18/970-ipraktikum-ss18) at TUM
- responsible for creating and improving the user interface for hands-off interaction with the devices using Augmented Reality from iOS [ARKit](https://developer.apple.com/augmented-reality/) to identify and interact with [Siematic IoT devices](https://new.siemens.com/global/en/products/automation/pc-based/iot-gateways/iot2000.html). The identification of these devices was made possible using ML model made by the team during university project.
- part of my job was related to gathering logging and sensor data (both digital and analogue) from Siematic 2040 devices to [Siemens MindSphere IoT Cloud](https://siemens.mindsphere.io/en) using [mraa](http://iotdk.intel.com/docs/master/mraa/python/).

### [maiot GmbH](https://www.linkedin.com/company/maiot/)

**Apr 2018 &rarr; Sept 2018**

_Munich, Germany_

- Software Engineering Intern for a mandatory [Interdisciplinary Project](https://www.in.tum.de/en/current-students/masters-programs/informatics/interdisciplinary-project/fpo-2012-and-2016-and-2018/) during MSc. Informatiks at [TUM](https://www.tum.de/en/)
- Worked closely with CTO and other team members in setting up experimental data streaming pipelines using [Google PubSub](https://cloud.google.com/pubsub) and [Apache Beam](https://beam.apache.org/) to ingest and preprocess data for predictive maintenance of trucks.
- Performed data analysis and visualisation using [ELK stack](https://www.elastic.co/what-is/elk-stack)
- Explored data trends in ingested data in [Google Bigtable](https://cloud.google.com/bigtable) using [Google DataStudio](https://datastudio.google.com/)

### [Technical University of Munich](https://www.linkedin.com/school/technische-universitat-munchen/)

**Apr 2018 &rarr; Aug 2018**

_Munich, Germany_

- Tutored students of the [Introduction to Software Engineering](https://ase.in.tum.de/lehrstuhl_1/teaching/summer-2018/121-teaching/st18/963-eist-2018) course at the Chair of Applied Software Engineering
- Helped students in understanding the course content and exercises, which spanned software modeling, software development lifecycle, system design, object oriented design, testing and project organization.
- Conducted 3hr long weekly tutorials and lecture explanation for a group of over 50 students

### [NetSol Technologies Inc.](https://www.linkedin.com/company/netsol-technologies-inc-/)

**Jul 2015 &rarr; Aug 2017**

_Lahore, Pakistan_

- Software Engineer with a focus towards fullstack [dotNET framework](https://dotnet.microsoft.com/en-us/) application development
- Developed and maintained features for autoleasing and autofinancing clients on Netsol Financial Suite ( or [NFS Ascent](https://netsoltech.com/nfs-ascent) ) in a team of 25 people, including PM, Team Lead, Business Analysts, testing, database management and deployment groups.
- Participated in software development lifecycle, with ranging from requirement gathering from client, writing functional documents, creating stories and tasks in [JIRA](https://www.atlassian.com/software/jira), estimation of effort and sprint planning, developing, testing of modules and deployment.
- Tech stack included Microsoft [Silverlight](https://www.microsoft.com/silverlight/) for frontend application, [SOAP](https://en.wikipedia.org/wiki/SOAP) as messaging protocol, Microsoft [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2019) as database and [ASP.net](https://dotnet.microsoft.com/en-us/apps/aspnet) for backend services.

### [oDesk](https://www.linkedin.com/company/odesk/)

**Feb 2015 &rarr; Jul 2017**

_remote_

- Freelanced on projects on Android and iOS
- Learned about understaing requirements from the clients and leading solo software engineering projects.

### [Punjab Information Technology Board](https://www.linkedin.com/company/punjab-information-technology-board/)

**Oct 2015 &rarr; Mar 2016**

_Lahore, Pakistan_

- Worked on the inital draft of an android application to [help provincial government track immunization records of new born babies](https://www.facebook.com/Har.Zindagi.Every.life.matters/) across the province of Punjab.
- I was responsible for creating an android application which could work in low network coverage and was able to transmit information through an NFC chip implanted on every health care card issued to new born babies. The data would then sync with remote servers once there is availability of network coverage.

## Education

### [Technical University of Munich](https://www.linkedin.com/school/technische-universitat-munchen/)

**Oct 2017 &rarr; Aug 2020**

_Munich, Germany_

- Completed my MSc. Informatiks with a focus towards Software engineering and Distributed systems
- Took courses in patterns of software engineering, cloud computing, peer-to-peer networks, with practical courses in iOS development and automated diagnosis of drone crashes and web development using [mern stack](https://www.mongodb.com/mern-stack).
- Wrote my master's thesis with chair of Business Information Systems, on the topic of `Profiling scalable storage solutions for distributed deep learning`, where my goal was to identify and provide remedial recommentations for storage bottlenecks in image recognition and natural language processing pipelines.

### [National University of Computer and Emerging Sciences](https://www.linkedin.com/school/fastnu/)

**Aug 2011 &rarr; Aug 2016**

_Lahore, Pakistan_

- Completed my BSc. Computer Science with a focus towards Software engineering
- Took courses in software engineering, object oriented programming, algorithms and data structures, advanced programming with topics such as thread safe coding, multiprocessing and memory management, artificial intelligence, human computer interaction, probability and statistics, linear algebra and higher order differential equations.
- Topic of my bachelors's thesis was investigating and finding a solution for detecting `Heart valvular disease detection using Phonocardiogram signals`, which aimed towards identifying valvular heart diseases in patients using a smart phone.

## Certifications and Awards

### [flyte hackathon 2022 - remote](https://flyte.org/hackathon/)

- _flyte and union.ai_
- Ranked 3rd amongst 11 competing teams and won cash prize and an opportunity to contribute to official flyte repo with our work as example code
- Gave a presentation of our (me along with my group partner) work on [MLOps Community meetup session](https://www.youtube.com/watch?v=OLD5-G9R9fw)

### [AWS Certified Solutions Architect - Associate](https://www.credly.com/badges/bdb44bdf-d7fb-4898-b527-d9db6056db37)

- _Amazon Web Services_
- **Issued Sept 2021 &rarr; Expires Sept 2024**

### [KubeCon + CloudNativeCon Europe 2021 - Virtual](https://events.linuxfoundation.org/kubecon-cloudnativecon-europe/)

- _KubeCon_
- **Issued May 2021**
- I received scholarship from KubeCon and CloudNativeCon Europe, managed by CNCF and Linux Foundation, to attend the event worth hundreds of dollars.

### [KubeCon + CloudNativeCon North America](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/)

- _KubeCon_
- **Issued Nov 2020**
- I received scholarship from KubeCon and CloudNative North America, managed by CNCF and Linux Foundation, to attend the event worth hundreds of dollars.

### [Elastic Google Cloud Infrastructure: Scaling and Automation](https://www.coursera.org/account/accomplishments/verify/F6YQKLV4PTUC)

- _Coursera_
- **Issued Mar 2020 &rarr; No Expiration date**

### [Essential Google Cloud Infrastructure: Core Services](https://www.coursera.org/account/accomplishments/certificate/S9TX8TZ3JJ2S)

- _Coursera_
- **Issued Jan 2020 &rarr; No Expiration date**

### [Essential Google Cloud Infrastructure: Foundation](https://www.coursera.org/account/accomplishments/verify/V6C9JUQCRYJF)

- _Coursera_
- **Issued Jan 2020 &rarr; No Expiration date**

### [Siemens Global University Challenge 2018 - Nuremberg](https://ase.in.tum.de/lehrstuhl_1/siemens-ipraktium-team-iot-is-among-the-10-winners-of-the-siemens-global-university-challenge)

- _Siemens AG_
- This hackathon was the continuation of my iOS praktikum project, which made its way to the final 10 projects and eventually sweeped the prize for Most Innovative Idea.

## Hackathons

- [HackZurich](https://hackzurich.com/) 2022 (participant)
- [flyte Online Hackathon](https://flyte.org/hackathon/) 2022 (Third place award along with prize money and merch!)
- [HackZurich](https://hackzurich.com/) 2021 (participant)
- [HackZurich](https://hackzurich.com/) 2019 (Runner up for Credit Suisse Award)
- [hackaTUM](https://hack.tum.de/) 2019 (participant)
- [Siemens Global University Challenge](https://ase.in.tum.de/lehrstuhl_1/siemens-ipraktium-team-iot-is-among-the-10-winners-of-the-siemens-global-university-challenge) 2018 - Nuremberg (Most Innovative Idea award)
- [hackaTUM](https://hack.tum.de/) 2018 - (participant)
- [HackZurich](https://hackzurich.com/) 2018 (participant)

## Projects

- **Music genre classification pipeline**: Pipeline built on [flyte](https://flyte.org/) for training [GTZAN dataset](https://huggingface.co/datasets/marsyas/gtzan) using Tensorflow, tracking using [Weights and Biases](https://wandb.ai/site) and deployment using [StreamLit](https://streamlit.io/)
- **Iris classification pipeline**: Pipeline built on [flyte](https://flyte.org/) for training Iris dataset using Pytorch and tracking using [Weights and Biases](https://wandb.ai/site)
- **Fashion MNIST pipeline**: Pipeline built on MetaFlow for training Fashion MNIST using Pytorch, MLFlow and BentoML
- **Digit MNIST pipeline**: Pipeline built on ZenML for training MNIST using Pytorch, MLFlow and BentoML
- **Cafe around the Corner**: Location based web application for cozy coffee shops in Munich
- **Siemoji**: An iOS application to assist maintenance of IoT fleet
- **Har Zindagi**: An android app for tracking child immunization activities in rural areas of Pakistan

## Skills and Competencies

- **Languages**: Python, Go, Typescript, Swift, C++, C, Java, C#, SQL, Javascript
- **Data Science stack**: Jupyter, Pandas, numpy, seaborn, XGBoost, lightbgm, dvc, Airflow, ELK stack
- **Infrastructure**: AWS, Azure, GCP, terraform, terragrunt, pulumi, buildkite, Gitlab CI/CD, Github Actions, docker, Kubernetes
- **Web**: Flask, Gunicorn, Uvicorn, React, Django, Typescript, Python, Google APIs, MongoDb, node.js, Swagger
- **ML Framework**: Pytorch, ZenML, Metaflow, flyte, MLflow, BentoML, Kafka, Apache Beam
- **Mobile Development**: Android, iOS, Swift, Java, XCode, Android Studio
