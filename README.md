# DevOps Learning & Lab Portfolio
# DevOps Learning and Lab Manual

This repository documents my complete DevOps learning journey,
including prerequisite concepts, hands-on experiments, laboratory
exercises, troubleshooting, revision notes, and implementation history.
This repository contains the implementation and documentation of 10 DevOps laboratory exercises.

## Learning Approach
## Technologies
- Git and GitHub
- Docker and Docker Compose concepts
- Kubernetes and Minikube
- Python and Flask
- MySQL and Redis
- Prometheus and Grafana
- Jenkins CI/CD
- Linux and WSL2

Learn → Understand → Implement → Break → Troubleshoot → Explain → Document → Commit
## Laboratory Exercises

## Goals
| No. | Exercise | Status |
|-----|----------|--------|
| 01 | Kubernetes Deployment and Service | Completed |
| 02 | Dockerized Flask on Minikube | Completed |
| 03 | ReplicaSet Scaling and Self-Healing | Completed |
| 04 | Docker Networking with MySQL and Redis | Completed |
| 05 | Docker Security and Python SDK | Partially completed (AppArmor limitation) |
| 06 | Prometheus and Grafana Monitoring | Completed |
| 07 | Jenkins Installation and CI Job | Completed |
| 08 | Jenkins and GitHub Integration | Completed |
| 09 | Jenkins Multistage Pipeline | Completed |
| 10 | Multinode Kubernetes | Completed |

- Understand DevOps fundamentals
- Learn Linux and networking fundamentals
- Learn Docker and containerization
- Learn Kubernetes
- Learn monitoring with Prometheus and Grafana
- Learn CI/CD with Jenkins
- Complete all prescribed DevOps laboratory exercises
- Develop practical troubleshooting skills
- Prepare for DevOps-related viva and technical interviews
## Verification Highlights

## Repository Structure
- Flask applications tested using HTTP requests.
- ReplicaSet scaling and self-healing demonstrated.
- Docker container connectivity to MySQL and Redis verified.
- Docker Python SDK successfully managed containers.
- Prometheus collected application metrics.
- Grafana alert entered the Firing state.
- Jenkins Freestyle jobs completed successfully.
- Jenkins five-stage pipeline executed successfully.
- Three-node Minikube cluster reached Ready status.
- Product Catalog: 2/2 replicas Ready.
- Shopping Cart: 3/3 replicas Ready.
- Both Kubernetes services returned HTTP 200.

## Evaluation Preparation

- [Faculty Evaluation Guide](FACULTY_EVALUATION.md)
- [Revision Notes](REVISION.md)
- [Troubleshooting Guide](TROUBLESHOOTING.md)
- [Progress Tracker](PROGRESS.md)
- [Roadmap](ROADMAP.md)

- `foundations/` — prerequisite learning and experiments
- `exercise-01-kubernetes/` — Kubernetes Getting Started
- `exercise-02-minikube-flask/` — Flask deployment on Minikube
- `exercise-03-replicaset/` — ReplicaSets and scaling
- `exercise-04-docker-networking/` — Docker networking
- `exercise-05-docker-security/` — Docker security and AppArmor
- `exercise-06-monitoring/` — Prometheus and Grafana
- `exercise-07-jenkins/` — Jenkins fundamentals
- `exercise-08-jenkins-github/` — Jenkins + GitHub
- `exercise-09-jenkins-pipeline/` — Jenkins CI/CD pipeline
- `exercise-10-multinode-kubernetes/` — Multi-node Kubernetes
## Important Notes

- AppArmor enforcement was not available in the Docker Desktop/WSL2 environment.
- Jenkins GitHub integration was tested with manual builds, not automatic webhooks.
- Product Catalog and Shopping Cart are demonstration Nginx workloads.
- Grafana dashboards and alerts were configured through the Grafana interface.

## Repository Structure

## Progress
Each exercise has its own directory containing the available source code,
configuration files, Kubernetes manifests, Jenkinsfile, and/or README documentation.

Current Phase: DevOps & Linux Foundations
## Conclusion

Current Day: Day 01
All 10 laboratory exercises have been documented, with implementation
results, verification, and known limitations recorded.
