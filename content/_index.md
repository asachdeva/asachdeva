---
title: CV
---
# Akshay Sachdeva
I am a software engineer.
I prefer a pure functional programming approach to design and implementation to provide high performance and modular
solutions.
Cloud Engineering Savvy (GCP |+| AWS |+| Azure).
I love OSS and welcome the growth from engaging in contributions and learning from the community.

{{% grid %}}

{{% column -span-cols-6 -m-right-2 %}}

## Professional Experience
###### *March 2019 - Present*
### Dell Inc — Sr Principal Engineer -- Research in Advanced Engineering
Working on Streaming DataPipeline hosted at Azure utilizing Kubernetes to help acquire, transform and mine real time
signals from Dell devices, storage and network components at a massive scale to enable Data Scientists run better
models faster and more importantly more pre emptively for a better support infrastructure

* -- Scala with zio-streams, http4s, cats.
* Data Visualization -- Prometheus + Grafana
* Azure

Responsible for designing, architecting and implementing this offering on scala 2.12 and a mix of typelevel libs in
cats, circe, http4s and zio for stream and stream combinators.  Build and Deployments is using GitLab and k8s+Terraform
to provision.  Also researching Graph DB and GraphQL approach for an Enterprise Knowledge Graph solution for the fraud
detection and support assist teams.

###### August 2019 - May 2020*
### Citrine Informatics — Senior Software Engineer (Remote)
Worked on Machine Learning REST Service hosted at AWS utilizing EC2 to enable an application for Citrine to serve its ML
Library built on Scala.  The REST service interacted with a Data Service Component (Dynamo DB + Postgres) and integrated
with a TypeScript REST API that provided authentication and authoriziation leveraging JWT.

* -- Scala with Akka(Actors, Http, Streams), cats, json4s, cats-effect et al
* AWS (SQS, Cloudwatch, EC2, DynamoDB, S3, Lambda, AWS Batch)
* Data Visualization -- Monitoring Service + statsD + DataDog + AWS Lambda to move data from Cloudwatch to Datadog

Responsible for implementing and refactoring this service built on scala 2.12 to migrate to a pure FP approach using cats +
cats-effects and bringing better testing approach using scalacheck.  Build and Deployments was using Pants + Jenkins +
CF/Jssonet templates

###### August 2017 - March 2019
### Spiceworks Inc — Staff Data Engineer
Worked on Streaming Data Pipeline to support a RTB (Real Time Bidding) for the adtech space.  The Pipeline had 23
microservices that were deployed on AWS on EKS with Monitoring support using DataDog.  The Persistence stores ranged
from RDS(Schema ereg), to Redis(cache and lookup), to Cassandra(Graph + History), to DynamoDB and AthenaDB(datalake),
and finally to Kafka as data backplane.
Orchestration and ETL was built using Airflow (Python 3.6)
The RTB stack was built on GoLang

* -- Scala with Akka(Actors, Http, Streams, Persistence), fs2, cats, cats-effect, circe, doobie, shapeless, sangria, Gatling et al
* AWS (Kinesis, Eks, Athena, Lambda, Glue)
* Heavy use of Kafka
* Data Visualiztion migrated from Eks to NewRelic to DataDog

Responsible for implementing and refactoring this service built on scala 2.12 and later to migrate to a pure FP approach using cats +
fs2 and http4s and bringing better testing approach using scalacheck.  Build and Deployments was using sbt + Gitlab +
k8s + Terraform.

###### August 2012 - March 2017
### Advisory Board Inc — Senior Software Engineer
Towards the end worked on Data Pipeline (Batch+Streaming) to support a DataHub Initiative for the healthcare space.  The Pipeline was a
spark application built around Kafka and used HDFS as a Sink. Persistence ranged from S3 to Postgres to Kafka.

* -- Scala with spark, spark-job-server, Gatling et al
* AWS (EMR + CF)
* Heavy use of Kafka
* Data Visualiztion using ELK stack

Responsible for designing, implementing this application built on scala 2.11 and spark.  Build and Deployments were using
an Atlassian Stack in Bamboo and then Gradle to build the artifacts.  Additionally at this company I also worked on
projects that included Search Infra (Elastic Search) and a Readmission application using Node.js/Java/Guice, Spring.

Previous to this I worked at Escalation Point (Java Developer), Zilliant (Solution Architect in Price Optimiation),
SiteStuff Inc (Developer/Development Manager), Fusion Learning Systems (Technical Architect), IBM (Appication
Developer), Trilogy Software (Developer/Consultant).  These experiences stretched from 1998 through 2012.

{{% /column %}}

{{% column -span-cols-4 -p-left-3 %}}
#### Fluent with
  * Scala (Typelevel + Zio)
  * Java
  * Spark (unfortunately)

#### Familiar with
  * Python
  * GoLang
  * JS (Node + React)

#### Interested in
  * Pure Functional Programming
  * Category Theory
  * Evolving at FP
  * Machine Learning in the Stream (Storm + Flink + Apache Heron + Google Data Flow)

#### Educational Info
{{% dd %}}
- **Degree from University of Texas at Austin:**
  1. BS - Computer Science with minor in Math
  2. BA - Economics
{{% /dd %}}


## Hobbies/Interests
I have interests...cooking, traveling, yoga, rainforests, road biking, music

{{% printonly %}}
##   References
Please contact me at [asachdeva@utexas.edu](mailto:asachdeva@utexas.edu)
{{% /printonly %}}

{{% /column %}}
{{% /grid %}}
