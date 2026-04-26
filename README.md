# Awesome Docker [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)][sindresorhus] [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/veggiemonk/awesome-docker/)[![Last Commit](https://img.shields.io/github/last-commit/veggiemonk/awesome-docker)](https://github.com/veggiemonk/awesome-docker/commits/main) ⭐ 35,870 | 🐛 13 | 📅 2026-04-23<!-- omit in toc --> with stars

> A curated list of Docker resources and projects

If you would like to contribute, please read [CONTRIBUTING.md][contributing] first.
It contains a lot of tips and guidelines to help keep things organized.
Just click [README.md][editreadme] to submit a [pull request][editreadme].
If this list is not complete, you can [contribute][editreadme] to make it so. Here is a great video tutorial to learn how to [contribute on Github](https://egghead.io/lessons/javascript-identifying-how-to-contribute-to-an-open-source-project-on-github).

> **Please**, help organize these resources so that they are *easy to find* and *understand* for newcomers. See how to **[Contribute][contributing]** for tips!

***If you see a link here that is not (any longer) a good fit, you can fix it by submitting a [pull request][editreadme] to improve this file. Thank you!***

The creators and maintainers of this list do not receive any form of payment to accept a change made by any contributor. This page is not an official Docker product in any way. It is a list of links to projects and is maintained by volunteers. Everybody is welcome to contribute. The goal of this repo is to index open-source projects, not to advertise for profit.

# Contents <!-- omit in toc -->

<!-- TOC -->

* [Legend](#legend)
* [What is Docker](#what-is-docker)
* [Where to start](#where-to-start)
* [Where to start (Windows)](#where-to-start-windows)
* [Projects](#projects)
  * [Container Operations](#container-operations)
    * [Container Composition](#container-composition)
    * [Deployment and Infrastructure](#deployment-and-infrastructure)
    * [Monitoring](#monitoring)
    * [Networking](#networking)
    * [Orchestration](#orchestration)
    * [PaaS](#paas)
    * [Reverse Proxy](#reverse-proxy)
    * [Runtime](#runtime)
    * [Security](#security)
    * [Service Discovery](#service-discovery)
    * [Volume Management / Data](#volume-management--data)
    * [User Interface](#user-interface)
      * [IDE integrations](#ide-integrations)
      * [Desktop](#desktop)
      * [Terminal](#terminal)
        * [Terminal UI](#terminal-ui)
        * [CLI tools](#cli-tools)
        * [Other](#other)
      * [Web](#web)
  * [Docker Images](#docker-images)
    * [Base Tools](#base-tools)
    * [Builder](#builder)
    * [Dockerfile](#dockerfile)
    * [Linter](#linter)
    * [Metadata](#metadata)
    * [Registry](#registry)
  * [Development with Docker](#development-with-docker)
    * [API Client](#api-client)
    * [CI/CD](#cicd)
    * [Development Environment](#development-environment)
    * [Garbage Collection](#garbage-collection)
    * [Serverless](#serverless)
    * [Testing](#testing)
    * [Wrappers](#wrappers)
  * [Services based on Docker (mostly :yen:)](#services-based-on-docker-mostly-yen)
    * [CI Services](#ci-services)
    * [CaaS](#caas)
    * [Monitoring Services](#monitoring-services)
* [Useful Resources](#useful-resources)
  * [Awesome Lists](#awesome-lists)
  * [Demos and Examples](#demos-and-examples)
  * [Good Tips](#good-tips)
  * [Raspberry Pi & ARM](#raspberry-pi--arm)
  * [Security](#security-1)
  * [Videos](#videos)
* [Communities and Meetups](#communities-and-meetups)
  * [Brazilian](#brazilian)
  * [English](#english)
  * [Russian](#russian)
  * [Spanish](#spanish)
  * [Stargazers over time](#stargazers-over-time)

<!-- /TOC -->

# Legend

* Monetized :yen:
* Stale (2+ years inactive) :ice\_cube:

# What is Docker

> Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications. Consisting of Docker Engine, a portable, lightweight runtime and packaging tool, and Docker Hub, a cloud service for sharing applications and automating workflows, Docker enables apps to be quickly assembled from components and eliminates the friction between development, QA, and production environments. As a result, IT can ship faster and run the same app, unchanged, on laptops, data center VMs, and any cloud.

*Source:* [What is Docker](https://www.docker.com/why-docker/)

# Where to start

* [Docker Curriculum](https://github.com/prakhar1989/docker-curriculum) ⭐ 6,035 | 🐛 94 | 🌐 SCSS | 📅 2026-02-04: A comprehensive tutorial for getting started with Docker. Teaches how to use Docker and deploy dockerized apps on AWS with Elastic Beanstalk and Elastic Container Service.

* [Setting Python Development Environment with VScode and Docker](https://github.com/RamiKrispin/vscode-python) ⭐ 952 | 🐛 4 | 🌐 Shell | 📅 2024-02-02: A step-by-step tutorial for setting up a dockerized Python development environment with VScode, Docker, and the Dev Container extension.

* [Dockerlings](https://github.com/furkan/dockerlings) ⭐ 884 | 🐛 0 | 🌐 Shell | 📅 2026-03-22: Learn docker from inside your terminal, with a modern TUI and bite sized exercises (by [furkan](https://github.com/furkan))

* [The Docker Handbook](https://docker-handbook.farhan.dev/) An open-source book that teaches you the fundamentals, best practices and some intermediate Docker functionalities. The book is hosted on [fhsinchy/the-docker-handbook](https://github.com/fhsinchy/the-docker-handbook) ⭐ 867 | 🐛 5 | 📅 2026-04-02 and the projects are hosted on [fhsinchy/docker-handbook-projects](https://github.com/fhsinchy/docker-handbook-projects) ⭐ 1,393 | 🐛 3 | 🌐 JavaScript | 📅 2026-04-02 repository.

* [Docker katas](https://github.com/eficode-academy/docker-katas) ⭐ 289 | 🐛 13 | 🌐 Dockerfile | 📅 2026-02-20 A series of labs that will take you from "Hello Docker" to deploying a containerized web application to a server.

* [Practical Guide about Docker Commands in Spanish](https://github.com/brunocascio/docker-espanol) ⭐ 253 | 🐛 1 | 🌐 Ruby | 📅 2020-07-15 This Spanish guide contains the use of basic docker commands with real life examples.

* [Learn Docker](https://github.com/dwyl/learn-docker) ⭐ 243 | 🐛 10 | 🌐 Dockerfile | 📅 2024-01-22: step-by-step tutorial and more resources (video, articles, cheat sheets) by [dwyl](https://github.com/dwyl)

* [Docker for beginners](https://github.com/groda/big_data/blob/master/docker_for_beginners.md) ⭐ 85 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-04-13: A tutorial for beginners who need to learn the basics of Docker—from "Hello world!" to basic interactions with containers, with simple explanations of the underlying concepts.

* [Benefits of using Docker](https://semaphore.io/blog/docker-benefits) for development and delivery, with a practical roadmap for adoption.

* [Bootstrapping Microservices](https://www.manning.com/books/bootstrapping-microservices-with-docker-kubernetes-and-terraform) - A practical and project-based guide to building applications with microservices, starts by building a Docker image for a single microservice and publishing it to a private container registry, finishes by deploying a complete microservices application to a production Kubernetes cluster.

* [Docker Documentation](https://docs.docker.com/): the official documentation.

* [Docker for novices](https://www.youtube.com/watch?v=xsjSadjKXns) An introduction to Docker for developers and testers who have never used it. (Video 1h40, recorded linux.conf.au 2019 — Christchurch, New Zealand) by Alex Clews.

* [Docker simplified in 55 seconds](https://www.youtube.com/watch?v=vP_4DlOH1G4): An animated high-level introduction to Docker. Think of it as a visual tl;dr that makes it easier to dive into more complex learning materials.

* [Docker Training](https://training.mirantis.com) :yen:

* [Introduction à Docker](https://blog.stephane-robert.info/docs/conteneurs/moteurs-conteneurs/docker/) A dedicated section to master Docker on a French site about DevSecOps: From the basics to best practices, including optimizing, securing your containers...

* [Learn Docker (Visually)](https://pagertree.com/learn/docker/overview) - A beginner-focused high-level overview of all the major components of Docker and how they fit together. Lots of high-quality images, examples, and resources.

* [Play With Docker](https://training.play-with-docker.com/): PWD is a great way to get started with Docker from beginner to advanced users. Docker runs directly in your browser.

**Cheatsheets** by

* [wsargent](https://github.com/wsargent/docker-cheat-sheet) ⭐ 22,512 | 🐛 7 | 📅 2024-12-31 (Most popular)
* [eon01](https://github.com/eon01/DockerCheatSheet) ⭐ 3,933 | 🐛 1 | 📅 2026-02-19
* [dimonomid](https://github.com/dimonomid/docker-quick-ref) ⭐ 198 | 🐛 1 | 🌐 Makefile | 📅 2021-09-26 (PDF)
* [JensPiegsa](https://github.com/JensPiegsa/docker-cheat-sheet) ⭐ 22 | 🐛 0 | 🌐 CSS | 📅 2022-03-23

# Where to start (Windows)

* [Docker on Windows behind a firewall](https://toedter.com/2015/05/11/docker-on-windows-behind-a-firewall/) by [kaitoedter](https://twitter.com/kaitoedter)
* [Docker Reference Architecture: Modernizing Traditional .NET Framework Applications](https://docs.mirantis.com/containers/v3.0/dockeree-ref-arch/app-dev/modernize-dotnet-apps.html) - You will learn to identify the types of .NET Framework applications that are good candidates for containerization, the "lift-and-shift" approach to containerization.
* [Docker with Microsoft SQL 2016 + ASP.NET](https://blog.alexellis.io/docker-does-sql2016-aspnet/) Demonstration running ASP.NET and SQL Server workloads in Docker
* [Exploring ASP.NET Core with Docker in both Linux and Windows Containers](https://www.hanselman.com/blog/exploring-aspnet-core-with-docker-in-both-linux-and-windows-containers) Running ASP.NET Core apps in Linux and Windows containers, using [Docker for Windows][docker-for-windows]
* [Running a Legacy ASP.NET App in a Windows Container](https://blog.sixeyed.com/dockerizing-nerd-dinner-part-1-running-a-legacy-asp-net-app-in-a-windows-container/) Steps for Dockerizing a legacy ASP.NET app and running as a Windows container
* [Windows Containers and Docker: The 101](https://www.youtube.com/watch?v=N7SG2wEyQtM) - A 20-minute overview, using Docker to run PowerShell, ASP.NET Core and ASP.NET apps.
* [Windows Containers Quick Start](https://learn.microsoft.com/en-us/virtualization/windowscontainers/about/) Overview of Windows containers, drilling down to Quick Starts for Windows 10 and Windows Server 2016

***

# Projects

* Moby = open source development
* Docker CE = free product release based on Moby
* Docker EE = commercial product release based on Docker CE.

> Docker EE is on the same code base as Docker CE, so also built from Moby, with commercial components added, such as "docker data center / universal control plane"

* [Moby](https://github.com/moby/moby) ⭐ 71,491 | 🐛 3,804 | 🌐 Go | 📅 2026-04-26
* [Docker Compose](https://github.com/docker/compose/) ⭐ 37,315 | 🐛 101 | 🌐 Go | 📅 2026-04-23 (Define and run multi-container applications with Docker)
* [Docker Images](https://hub.docker.com)
* [Docker Registry][distribution] (The Docker toolset to pack, ship, store, and deliver content)

## Container Operations

### Container Composition

* [kompose](https://github.com/kubernetes/kompose) ⭐ 10,508 | 🐛 16 | 🌐 Go | 📅 2026-04-16 - Go from Docker Compose to Kubernetes.
* [podman-compose](https://github.com/containers/podman-compose) ⭐ 6,054 | 🐛 384 | 🌐 Python | 📅 2026-04-22 - A script to run docker-compose.yml using podman.
* [Composerize](https://github.com/magicmark/composerize) ⭐ 3,730 | 🐛 12 | 🌐 JavaScript | 📅 2026-01-17 - Convert docker run commands into docker-compose files.
* [LLM Harbor](https://github.com/av/harbor) ⭐ 2,870 | 🐛 55 | 🌐 TypeScript | 📅 2026-04-25 - A CLI and companion app to effortlessly run LLM backends, APIs, frontends, and services with one command. By [av](https://github.com/av).
* [habitus](https://github.com/cloud66-oss/habitus) ⭐ 1,395 | 🐛 8 | 🌐 Go | 📅 2020-02-05 :ice\_cube: - A Build Flow Tool for Docker.
* [plash](https://github.com/ihucos/plash) ⭐ 384 | 🐛 9 | 🌐 C | 📅 2025-03-20 - A container run and build engine - runs inside docker.
* [ctk](https://github.com/ctk-hq/ctk) ⭐ 299 | 🐛 10 | 🌐 TypeScript | 📅 2026-02-15 - Visual composer for container based workloads. By [corpulent](https://github.com/corpulent).
* [crowdr](https://github.com/polonskiy/crowdr) ⭐ 98 | 🐛 0 | 🌐 Shell | 📅 2020-10-09 :ice\_cube: - Tool for managing multiple Docker containers (`docker-compose` alternative).
* [elsy](https://github.com/cisco/elsy) ⭐ 80 | 🐛 13 | 🌐 Go | 📅 2022-01-18 :ice\_cube: - An opinionated, multi-language, build tool based on Docker and Docker Compose.
* [docker-config-update](https://github.com/sudo-bmitch/docker-config-update) ⭐ 52 | 🐛 1 | 🌐 Shell | 📅 2023-03-30 :ice\_cube: - Utility to update docker configs and secrets for deploying in a compose file.
* [Smalte](https://github.com/roquie/smalte) ⭐ 36 | 🐛 1 | 🌐 Nim | 📅 2021-12-08 – Dynamically configure applications that require static configuration in docker container. By [roquie](https://github.com/roquie)
* [Capitan](https://github.com/byrnedo/capitan) ⭐ 31 | 🐛 3 | 🌐 Go | 📅 2017-06-07 :ice\_cube: - Composable docker orchestration with added scripting support by [byrnedo].
* [Stitchocker](https://github.com/alexaandrov/stitchocker) ⭐ 30 | 🐛 2 | 🌐 Shell | 📅 2024-03-14 - A lightweight and fast command line utility for conveniently grouping your docker-compose multiple container services. By [alexaandrov](https://github.com/alexaandrov).

### Deployment and Infrastructure

* [werf](https://github.com/werf/werf) ⭐ 4,682 | 🐛 146 | 🌐 Go | 📅 2026-04-24 - Werf is a CI/CD tool for building Docker images efficiently and deploying them to Kubernetes using GitOps.
* [gitkube](https://github.com/hasura/gitkube) ⭐ 3,848 | 🐛 44 | 🌐 Go | 📅 2023-08-31 :ice\_cube: - Gitkube is a tool for building and deploying docker images on Kubernetes using `git push`. By [Hasura](https://github.com/hasura/).
* [Grafeas](https://github.com/grafeas/grafeas) ⭐ 1,563 | 🐛 61 | 🌐 Go | 📅 2026-03-26 - A common API for metadata about containers, from image and build details to security vulnerabilities. By [grafeas](https://github.com/grafeas).
* [awesome-stacks](https://github.com/ethibox/awesome-stacks) ⭐ 1,276 | 🐛 9 | 🌐 Dockerfile | 📅 2026-04-17 - Deploy 150+ open-source web apps with one Docker command.
* [Clocker](https://github.com/brooklyncentral/clocker) ⭐ 429 | 🐛 53 | 🌐 Shell | 📅 2018-10-24 :ice\_cube: - Clocker creates and manages a Docker cloud infrastructure. Clocker supports single-click deployments and runtime management of multi-node applications that run as containers distributed across multiple hosts, on both Docker and Marathon. It leverages [Calico][calico] and [Weave][weave] for networking and [Brooklyn](https://brooklyn.apache.org/) for application blueprints. By [brooklyncentral](https://github.com/brooklyncentral).
* [Conduit](https://github.com/ehazlett/conduit) ⭐ 108 | 🐛 6 | 🌐 Go | 📅 2016-11-07 :ice\_cube: - Experimental deployment system for Docker.
* [depcon](https://github.com/ContainX/depcon) ⭐ 93 | 🐛 6 | 🌐 Go | 📅 2018-06-05 :ice\_cube: - Depcon is written in Go and allows you to easily deploy Docker containers to Apache Mesos/Marathon, Amazon ECS and Kubernetes. By [ContainX][containx].
* [swarm-ansible](https://github.com/LombardiDaniel/swarm-ansible?tab=readme-ov-file) ⭐ 59 | 🐛 0 | 🌐 HCL | 📅 2026-03-10 - Swarm-Ansible bootstraps a production-ready swarm cluster using ansible. Comes with tools to automate CI, help monitoring and traefik pre-configured for SSL certificates and simple-auth. Comes with a private registry and more!.
* [docker-to-iac](https://github.com/deploystackio/docker-to-iac) ⭐ 21 | 🐛 18 | 🌐 TypeScript | 📅 2026-03-20 - Translate docker run and commit into Infrastructure as Code templates for AWS, Render.com and DigitalOcean.
* [SwarmManagement](https://github.com/hansehe/SwarmManagement) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2025-05-13 - Swarm Management is a python application, installed with pip. The application makes it easy to manage a Docker Swarm by configuring a single yaml file describing which stacks to deploy, and which networks, configs or secrets to create.
* [blackfish](https://gitlab.com/blackfish/blackfish) - A CoreOS VM to build swarm clusters for Dev & Production.
* [BosnD](https://gitlab.com/n0r1sk/bosnd) - BosnD, the boatswain daemon - A dynamic configuration file writer & service reloader for dynamically changing container environments.

### Monitoring

* [Glances](https://github.com/nicolargo/glances) ⭐ 32,319 | 🐛 100 | 🌐 Python | 📅 2026-04-23 - A cross-platform curses-based system monitoring tool written in Python.

* [cAdvisor](https://github.com/google/cadvisor) ⭐ 19,083 | 🐛 93 | 🌐 Go | 📅 2026-04-16 - Analyzes resource usage and performance characteristics of running containers.

* [Checkmate](https://github.com/bluewave-labs/checkmate) ⭐ 9,687 | 🐛 102 | 🌐 TypeScript | 📅 2026-04-26 - Checkmate is an open-source, self-hosted tool designed to track and monitor server hardware, uptime, response times, and incidents in real-time with beautiful visualizations.

* [HertzBeat](https://github.com/dromara/hertzbeat) ⭐ 7,182 | 🐛 317 | 🌐 Java | 📅 2026-04-21 - An open-source real-time monitoring system with custom-monitor and agentless.

* [dockprom](https://github.com/stefanprodan/dockprom) ⭐ 6,507 | 🐛 20 | 📅 2026-03-06 - Docker hosts and containers monitoring with Prometheus, Grafana, cAdvisor, NodeExporter and AlertManager.

* [Logspout](https://github.com/gliderlabs/logspout) ⭐ 4,697 | 🐛 108 | 🌐 Go | 📅 2023-07-11 :ice\_cube: - Log routing for Docker container logs.

* [Autoheal](https://github.com/willfarrell/docker-autoheal) ⭐ 1,846 | 🐛 60 | 🌐 Shell | 📅 2025-09-09 - Monitor and restart unhealthy docker containers automatically.

* [Sidekick](https://github.com/runsidekick/sidekick) ⭐ 1,609 | 🐛 5 | 🌐 Java | 📅 2023-06-29 :ice\_cube: - Open source live application debugger like Chrome DevTools for your backend. Collect traces and generate logs on-demand without stopping & redeploying your applications.

* [Zabbix Docker module](https://github.com/monitoringartist/Zabbix-Docker-Monitoring) ⭐ 1,192 | 🐛 14 | 🌐 C | 📅 2022-02-22 :ice\_cube: - Zabbix module that provides discovery of running containers, CPU/memory/blk IO/net container metrics. Systemd Docker and LXC execution driver is also supported. It's a dynamically linked shared object library, so its performance is (\~10x) better, than any script solution.

* [NexClipper](https://github.com/NexClipper/NexClipper) ⭐ 565 | 🐛 8 | 🌐 Go | 📅 2023-05-05 :ice\_cube: - NexClipper is the container monitoring and performance management solution specialized in Docker, Apache Mesos, Marathon, DC/OS, Mesosphere, Kubernetes.

* [Out-of-the-box Host/Container Monitoring/Logging/Alerting Stack](https://github.com/uschtwill/docker_monitoring_logging_alerting) ⭐ 540 | 🐛 8 | 🌐 Roff | 📅 2018-09-13 :ice\_cube: - Docker host and container monitoring, logging and alerting out of the box using cAdvisor, Prometheus, Grafana for monitoring, Elasticsearch, Kibana and Logstash for logging and elastalert and Alertmanager for alerting. Set up in 5 Minutes. Secure mode for production use with built-in [Automated Nginx Reverse Proxy (jwilder's)][nginxproxy].

* [InfluxDB, cAdvisor, Grafana](https://github.com/vegasbrianc/docker-monitoring) ⭐ 473 | 🐛 3 | 📅 2018-06-10 :ice\_cube: - InfluxDB Time series DB in combination with Grafana and cAdvisor.

* [Doku](https://github.com/amerkurev/doku) ⭐ 413 | 🐛 8 | 🌐 Python | 📅 2025-12-26 - Doku is a simple web-based application that allows you to monitor Docker disk usage. [amerkurev](https://github.com/amerkurev).

* [Drydock](https://github.com/CodesWhat/drydock) ⭐ 188 | 🐛 14 | 🌐 TypeScript | 📅 2026-04-26 - Container update monitoring with web dashboard, 23 registry providers, 20 notification triggers, and distributed agent architecture. By [CodesWhat](https://github.com/CodesWhat).

* [Maintenant](https://github.com/kolapsis/maintenant) ⭐ 178 | 🐛 2 | 🌐 Go | 📅 2026-04-21 - Self-discovering infrastructure monitoring for Docker and Kubernetes. Auto-detects containers via labels, with endpoint monitoring, heartbeats, TLS certificates, resource metrics, update intelligence, and a built-in status page. Single binary with embedded SPA. By [kolapsis](https://github.com/kolapsis).

* [Docker-Alertd](https://github.com/deltaskelta/docker-alertd) ⭐ 108 | 🐛 3 | 🌐 Go | 📅 2017-11-15 :ice\_cube: - Monitor and send alerts based on docker container resource usage/statistics.

* [Docker-Flow-Monitor](https://github.com/docker-flow/docker-flow-monitor) ⭐ 87 | 🐛 8 | 🌐 Go | 📅 2021-03-17 :ice\_cube: - Reconfigures Prometheus when a new service is updated or deployed automatically.

* [Zabbix Docker](https://github.com/gomex/docker-zabbix) ⭐ 52 | 🐛 8 | 🌐 Python | 📅 2017-07-28 :ice\_cube: - Monitor containers automatically using zabbix LLD feature.

* [monit-docker](https://github.com/decryptus/monit-docker) ⭐ 34 | 🐛 2 | 🌐 Python | 📅 2023-01-16 :ice\_cube: - Monitor docker containers resources usage or status and execute docker commands or inside containers. \[decryptus]\[decryptus].

* [SwarmAlert](https://github.com/gpulido/SwarmAlert) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2019-11-27 :ice\_cube: - Monitors a Docker Swarm and sends Pushover alerts when it finds a container with no healthy service task running.

* [Docker-Sentinel](https://github.com/Will-Luck/Docker-Sentinel) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2026-04-17 - Automated container updates with per-container policies, rollback safety, and a real-time web dashboard. By [Will-Luck](https://github.com/Will-Luck).

* [DockProbe](https://github.com/deep-on/dockprobe) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2026-04-11 - Lightweight Docker monitoring dashboard in a single container. Real-time metrics, 6 anomaly detection rules, Telegram alerts, and 16 automated security scans. Zero config, \~50MB RAM. By [DeepOn](https://github.com/deep-on).

* [ADRG](https://github.com/jaldertech/adrg) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-03-07 - Dynamic Docker resource governor using cgroups v2 to manage system load.

* [DLIA](https://github.com/zorak1103/dlia) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2026-04-21 - DLIA is an AI-powered Docker log monitoring agent that uses Large Language Models (LLMs) to intelligently analyze container logs, detect anomalies, and provide contextual insights over time. By [zorak1103](https://github.com/zorak1103).

* [Wiremap](https://github.com/codeofmario/wiremap) ⭐ 2 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-27 - A self-hosted visual Docker network topology explorer with real-time log streaming, live stats, embedded terminal, and container inspection. By [codeofmario](https://github.com/codeofmario).

* [DockProc](https://gitlab.com/n0r1sk/dockproc) - I/O monitoring for containers on processlevel.

* [Dozzle](origin/dozzle) - Monitor container logs in real-time with a browser or mobile device. [amir20](https://github.com/amir20).

* [Dynatrace](https://docs.dynatrace.com/docs/observe/infrastructure-observability/container-platform-monitoring) - :yen: Monitor containerized applications without installing agents or modifying your Run commands.

* [Grafana Docker Dashboard Template](https://grafana.com/grafana/dashboards/179-docker-prometheus-monitoring/) - A template for your Docker, Grafana and Prometheus stack [vegasbrianc][vegasbrianc].

### Networking

* [netshoot](https://github.com/nicolaka/netshoot) ⭐ 10,624 | 🐛 44 | 🌐 Shell | 📅 2026-04-16 - The netshoot container has a powerful set of networking tools to help troubleshoot Docker networking issues.
* [MyIP](https://github.com/jason5ng32/MyIP) ⭐ 10,166 | 🐛 0 | 🌐 Vue | 📅 2026-04-25 - All in one IP Toolbox. Easy to check all your IPs, IP geolocation, check for DNS leaks, examine WebRTC connections, speed test, ping test, MTR test, check website availability, whois search and more. By [jason5ng32](https://github.com/jason5ng32).
* [Flannel](https://github.com/coreos/flannel/) ⭐ 9,440 | 🐛 23 | 🌐 Go | 📅 2026-04-23 - Flannel is a virtual network that gives a subnet to each host for use with container runtimes. By [coreos][coreos].
* [Pipework](https://github.com/jpetazzo/pipework) ⭐ 4,253 | 🐛 5 | 🌐 Shell | 📅 2024-11-04 - Software-Defined Networking for Linux Containers, Pipework works with "plain" LXC containers, and with the awesome Docker. By [jpetazzo][jpetazzo].
* [Freeflow](https://github.com/Microsoft/Freeflow) ⭐ 635 | 🐛 14 | 🌐 C | 📅 2023-06-12 :ice\_cube: - High performance container overlay networks on Linux. Enabling RDMA (on both InfiniBand and RoCE) and accelerating TCP to bare metal performance. By [Microsoft](https://github.com/Microsoft).
* [Calico][calico] - Calico is a pure layer 3 virtual network that allows containers over multiple docker-hosts to talk to each other.

### Orchestration

* [Kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 121,926 | 🐛 2,673 | 🌐 Go | 📅 2026-04-26 - Open source orchestration system for Docker containers by Google.
* [Rancher](https://github.com/rancher/rancher) ⭐ 25,524 | 🐛 3,308 | 🌐 Go | 📅 2026-04-25 - An open source project that provides a complete platform for operating Docker in production.
* [Nomad](https://github.com/hashicorp/nomad) ⭐ 16,448 | 🐛 1,666 | 🌐 Go | 📅 2026-04-25 - Easily deploy applications at any scale. A Distributed, Highly Available, Datacenter-Aware Scheduler.
* [Mesos](https://github.com/apache/mesos) ⭐ 5,365 | 🐛 10 | 🌐 C++ | 📅 2024-08-23 - Resource/Job scheduler for containers, VM's and physical hosts [apache](https://mesos.apache.org/).
* [docker rollout](https://github.com/Wowu/docker-rollout) ⭐ 3,191 | 🐛 9 | 🌐 Shell | 📅 2026-04-02 - Zero downtime deployment for Docker Compose services.
* [ManageIQ](https://github.com/ManageIQ/manageiq) ⭐ 1,398 | 🐛 326 | 🌐 Ruby | 📅 2026-04-24 - Discover, optimize and control your hybrid IT. By [ManageIQ](https://github.com/ManageIQ).
* [Swarm-cronjob](https://github.com/crazy-max/swarm-cronjob) ⭐ 869 | 🐛 19 | 🌐 Go | 📅 2026-04-23 - Create jobs on a time-based schedule on Swarm by [crazy-max].
* [Crane](https://github.com/Dataman-Cloud/crane) ⭐ 749 | 🐛 15 | 🌐 Go | 📅 2023-08-31 :ice\_cube: - Control plane based on docker built-in swarm [Dataman-Cloud](https://github.com/Dataman-Cloud).
* [Haven](https://github.com/codeabovelab/haven-platform) ⭐ 298 | 🐛 8 | 🌐 Java | 📅 2018-07-06 :ice\_cube: - Haven is a simplified container management platform that integrates container, application, cluster, image, and registry managements. By [codeabovelab](https://github.com/codeabovelab).
* [CloudSlang](https://github.com/CloudSlang/cloud-slang) ⭐ 241 | 🐛 110 | 🌐 Java | 📅 2026-04-21 - CloudSlang is a workflow engine to create Docker process automation.
* [athena](https://github.com/athena-oss/athena) ⭐ 96 | 🐛 9 | 🌐 Shell | 📅 2017-07-06 :ice\_cube: - An automation platform with a plugin architecture that allows you to easily create and share services.
* [RedHerd Framework](https://github.com/redherd-project/redherd-framework) ⭐ 75 | 🐛 0 | 🌐 JavaScript | 📅 2023-04-25 :ice\_cube: - RedHerd is a collaborative and serverless framework for orchestrating a geographically distributed group of assets capable of simulating complex offensive cyberspace operations. By [RedHerdProject](https://github.com/redherd-project).
* [Docker Flow Swarm Listener](https://github.com/docker-flow/docker-flow-swarm-listener) ⭐ 68 | 🐛 6 | 🌐 Go | 📅 2019-05-20 :ice\_cube: - Docker Flow Swarm Listener project is to listen to Docker Swarm events and send requests when a change occurs. By [docker-flow][docker-flow].
* [Ansible Linux Docker](https://github.com/Peco602/ansible-linux-docker) ⭐ 39 | 🐛 0 | 🌐 Shell | 📅 2023-06-21 :ice\_cube: - Run Ansible from a Linux container. By [Peco602][peco602].
* [clusterdock](https://github.com/clusterdock/clusterdock) ⭐ 30 | 🐛 12 | 🌐 Python | 📅 2023-05-16 :ice\_cube: - Docker container orchestration to enable the testing of long-running cluster deployments.
* [Nebula](https://github.com/nebula-orchestrator) - A Docker orchestration tool designed to manage massive scale distributed clusters.

### PaaS

* [Dokku](https://github.com/dokku/dokku) ⭐ 31,860 | 🐛 41 | 🌐 Shell | 📅 2026-04-26 - Docker powered mini-Heroku that helps you build and manage the lifecycle of applications (originally by [progrium][progrium]).
* [caprover](https://github.com/caprover/caprover) ⭐ 14,986 | 🐛 177 | 🌐 TypeScript | 📅 2026-04-12 - \[Previously known as CaptainDuckDuck] Automated Scalable Webserver Package (automated Docker+nginx) - Heroku on Steroids.
* [Tsuru](https://github.com/tsuru/tsuru) ⭐ 5,271 | 🐛 30 | 🌐 Go | 📅 2026-04-24 - Tsuru is an extensible and open source Platform as a Service software.
* [Empire](https://github.com/remind101/empire) ⭐ 2,680 | 🐛 90 | 🌐 Go | 📅 2023-11-25 :ice\_cube: - A PaaS built on top of Amazon EC2 Container Service (ECS).
* [Convox Rack](https://github.com/convox/rack) ⭐ 1,893 | 🐛 24 | 🌐 Go | 📅 2026-04-21 - Convox Rack is open source PaaS built on top of expert infrastructure automation and devops best practices.
* [Nanobox](https://github.com/nanobox-io/nanobox) ⭐ 1,628 | 🐛 76 | 🌐 Go | 📅 2019-10-21 :ice\_cube: - :yen: An application development platform that creates local environments that can then be deployed and scaled in the cloud.
* [Exoframe](https://github.com/exoframejs/exoframe) ⭐ 1,150 | 🐛 17 | 🌐 JavaScript | 📅 2026-02-22 - A self-hosted tool that allows simple one-command deployments using Docker.
* [Hephy Workflow](https://github.com/teamhephy/workflow) ⭐ 419 | 🐛 81 | 🌐 SCSS | 📅 2023-09-27 :ice\_cube: - Open source PaaS for Kubernetes that adds a developer-friendly layer to any Kubernetes cluster, making it easy to deploy and manage applications. Fork of [Deis Workflow](https://github.com/deis/workflow) ⚠️ Archived.
* [Krane](https://github.com/krane/krane) ⭐ 85 | 🐛 10 | 🌐 Go | 📅 2023-05-11 :ice\_cube: - Toolset for managing container workloads on remote servers.
* [Dcw](https://github.com/pbertera/dcw) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2017-03-29 :ice\_cube: - Docker-compose SSH wrapper: a very poor man PaaS, exposing the docker-compose and custom-container commands defined in container labels.
* [OpenShift][openshift] - An open source PaaS built on [Kubernetes][kubernetes] and optimized for Dockerized app development and deployment by [Red Hat](https://www.redhat.com/en)

### Reverse Proxy

* [Træfɪk](https://github.com/containous/traefik) ⭐ 62,877 | 🐛 773 | 🌐 Go | 📅 2026-04-24 - Automated reverse proxy and load-balancer for Docker, Mesos, Consul, Etcd... By [EmileVauge](https://github.com/emilevauge).
* [Nginx Proxy Manager](https://github.com/jc21/nginx-proxy-manager) ⭐ 32,609 | 🐛 985 | 🌐 TypeScript | 📅 2026-04-24 - A beautiful web interface for proxying web based services with SSL. By [jc21](https://github.com/jc21).
* [BunkerWeb](https://github.com/bunkerity/bunkerweb) ⭐ 10,358 | 🐛 188 | 🌐 Python | 📅 2026-04-24 - Open-source and next-gen Web Application Firewall (WAF). By [Bunkerity](https://www.bunkerity.com).
* [Let's Encrypt Nginx-proxy Companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion) ⭐ 7,703 | 🐛 50 | 🌐 Shell | 📅 2026-04-16 - A lightweight companion container for the nginx-proxy. It allow the creation/renewal of Let's Encrypt certificates automatically. By [JrCs](https://github.com/JrCs).
* [fabio](https://github.com/fabiolb/fabio) ⭐ 7,333 | 🐛 239 | 🌐 Go | 📅 2026-04-21 - A fast, modern, zero-conf load balancing HTTP(S) router for deploying microservices managed by consul. By [magiconair](https://github.com/magiconair) (Frank Schroeder).
* [caddy-docker-proxy](https://github.com/lucaslorentz/caddy-docker-proxy) ⭐ 4,429 | 🐛 45 | 🌐 Go | 📅 2026-04-25 - Caddy-based reverse proxy, configured with service or container labels. By [lucaslorentz](https://github.com/lucaslorentz).
* [OpenResty Manager](https://github.com/Safe3/openresty-manager) ⭐ 1,357 | 🐛 55 | 🌐 Go | 📅 2026-01-25 - The easiest using, powerful and beautiful OpenResty Manager(Nginx Enhanced Version), open source alternative to OpenResty Edge. By [Safe3](https://github.com/Safe3/).
* [docker-flow-proxy](https://github.com/docker-flow/docker-flow-proxy) ⭐ 319 | 🐛 3 | 🌐 Go | 📅 2025-12-05 - Reconfigures proxy every time a new service is deployed, or when a service is scaled. By [docker-flow][docker-flow].
* [Swarm Router](https://github.com/flavioaiello/swarm-router) ⭐ 73 | 🐛 0 | 🌐 Dockerfile | 📅 2025-09-15 - A «zero config» service name based router for docker swarm mode with a fresh and more secure approach. By [flavioaiello](https://github.com/flavioaiello).
* [caddy-docker-upstreams](https://github.com/invzhi/caddy-docker-upstreams) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2025-09-08 - Docker upstreams module for Caddy, configured with container labels. By [invzhi](https://github.com/invzhi).
* [Docker Dnsmasq Updater](https://github.com/moonbuggy/docker-dnsmasq-updater) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2025-02-09 - Update a remote dnsmasq server with Docker container hostnames.
* [idle-less](https://github.com/tvup/idle-less) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2026-03-12 - Reverse proxy with automatic Wake-on-LAN — wakes sleeping backend servers when traffic arrives, shows a waiting screen, and redirects when ready. By [tvup](https://github.com/tvup).
* [mesh-router](https://github.com/Yundera/mesh-router) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-02 - Free domain(nsl.sh) provider for Docker containers with automatic HTTPS routing. Uses Wireguard VPN to securely route subdomain requests across networks. Ideal for self-hosted NAS and cloud deployments. By [Yundera](https://github.com/Yundera).
* [nginx-proxy][nginxproxy] - Automated nginx proxy for Docker containers using docker-gen by [jwilder][jwilder]

### Runtime

* [podman](https://github.com/containers/libpod) ⭐ 31,514 | 🐛 1,086 | 🌐 Go | 📅 2026-04-24 - Libpod is a library used to create container pods. Home of Podman.
* [cri-o](https://github.com/cri-o/cri-o) ⭐ 5,602 | 🐛 90 | 🌐 Go | 📅 2026-04-26 - Open Container Initiative-based implementation of Kubernetes Container Runtime Interface by [cri-o](https://github.com/cri-o).
* [lxc](https://github.com/lxc/lxc) ⭐ 5,169 | 🐛 169 | 🌐 C | 📅 2026-04-25 - LXC - Linux Containers.
* [runtime-tools](https://github.com/opencontainers/runtime-tools) ⭐ 479 | 🐛 70 | 🌐 Go | 📅 2026-03-16 - Oci-runtime-tool is a collection of tools for working with the OCI runtime specification.
* [Mocker](https://github.com/us/mocker) ⭐ 133 | 🐛 0 | 🌐 Swift | 📅 2026-04-25 - Docker-compatible container CLI for macOS, built on Apple's Containerization framework. By [us](https://github.com/us).
* [rlxc](https://github.com/brauner/rlxc) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2021-06-30 :ice\_cube: - LXC binary written in Rust.

### Security

* [Trivy](https://github.com/aquasecurity/trivy) ⭐ 34,704 | 🐛 243 | 🌐 Go | 📅 2026-04-24 - Aqua Security's open source simple and comprehensive vulnerability scanner for containers (suitable for CI).
* [Grype](https://github.com/anchore/grype) ⭐ 12,084 | 🐛 396 | 🌐 Go | 📅 2026-04-24 - A vulnerability scanner for container images, filesystems and SBOMs. By [Anchore](https://github.com/anchore).
* [Clair](https://github.com/quay/clair) ⭐ 10,969 | 🐛 47 | 🌐 Go | 📅 2026-04-24 - Clair is an open source project for the static analysis of vulnerabilities in appc and docker containers. By [coreos][coreos].
* [docker-bench-security](https://github.com/docker/docker-bench-security) ⭐ 9,623 | 🐛 27 | 🌐 Shell | 📅 2024-10-21 - Script that checks for dozens of common best-practices around deploying Docker containers in production. By [docker][docker].
* [Sysdig Falco](https://github.com/falcosecurity/falco) ⭐ 8,899 | 🐛 52 | 🌐 C++ | 📅 2026-04-24 - Sysdig Falco is an open source container security monitor. It can monitor application, container, host, and network activity and alert on unauthorized activity.
* [Syft](https://github.com/anchore/syft) ⭐ 8,816 | 🐛 588 | 🌐 Go | 📅 2026-04-24 - CLI tool and library for generating a Software Bill of Materials (SBOM) from container images and filesystems. By [Anchore](https://github.com/anchore).
* [Checkov](https://github.com/bridgecrewio/checkov) ⭐ 8,666 | 🐛 145 | 🌐 Python | 📅 2026-04-26 - Static analysis for infrastructure as code manifests (Terraform, Kubernetes, Cloudformation, Helm, Dockerfile, Kustomize) find security misconfiguration and fix them. By [bridgecrew](https://github.com/bridgecrewio).
* [Deepfence Threat Mapper](https://github.com/deepfence/ThreatMapper) ⭐ 5,255 | 🐛 142 | 🌐 TypeScript | 📅 2026-03-08 - Powerful runtime vulnerability scanner for kubernetes, virtual machines and serverless. By [deepfence][deepfence].
* [KICS](https://github.com/checkmarx/kics) ⭐ 2,624 | 🐛 299 | 🌐 Open Policy Agent | 📅 2026-04-22 - An infrastructure-as-code scanning tool, find security vulnerabilities, compliance issues, and infrastructure misconfigurations early in the development cycle. Can be extended for additional policies. By [Checkmarx](https://github.com/Checkmarx).
* [oscap-docker](https://github.com/OpenSCAP/openscap) ⭐ 1,707 | 🐛 60 | 🌐 XSLT | 📅 2026-04-23 - OpenSCAP provides oscap-docker tool which is used to scan Docker containers and images. By [OpenSCAP](https://github.com/OpenSCAP).
* [Dagda](https://github.com/eliasgranderubio/dagda) ⭐ 1,228 | 🐛 25 | 🌐 Python | 📅 2023-05-23 :ice\_cube: - Dagda is a tool to perform static analysis of known vulnerabilities, trojans, viruses, malware & other malicious threats in docker images/containers and to monitor the docker daemon and running docker containers for detecting anomalous activities. By [eliasgranderubio](https://github.com/eliasgranderubio).
* [bane](https://github.com/genuinetools/bane) ⭐ 1,226 | 🐛 4 | 🌐 Go | 📅 2020-09-17 :ice\_cube: - AppArmor profile generator for Docker containers.
* [docker-explorer](https://github.com/google/docker-explorer) ⚠️ Archived - A tool to help forensicate offline docker acquisitions.
* [CIS Docker Benchmark](https://github.com/dev-sec/cis-docker-benchmark) ⭐ 523 | 🐛 7 | 🌐 Ruby | 📅 2023-05-02 :ice\_cube: - This [InSpec][inspec] compliance profile implement the CIS Docker 1.12.0 Benchmark in an automated way to provide security best-practice tests around Docker daemon and containers in a production environment. By [dev-sec](https://github.com/dev-sec).
* [crowdsec-blocklist-import](https://github.com/wolffcatskyy/crowdsec-blocklist-import) ⭐ 200 | 🐛 3 | 🌐 Python | 📅 2026-04-20 - Aggregates 36 free threat intelligence feeds into 120k+ malicious IPs for CrowdSec bouncers, providing 10-20x more blocks than default lists. By [wolffcatskyy](https://github.com/wolffcatskyy).
* [CetusGuard](https://github.com/hectorm/cetusguard) ⭐ 83 | 🐛 2 | 🌐 Go | 📅 2026-04-01 - CetusGuard is a tool that protects the Docker daemon socket by filtering calls to its API endpoints.
* [Anchor](https://github.com/SongStitch/anchor/) ⭐ 24 | 🐛 1 | 🌐 Go | 📅 2025-01-15 - A tool to ensure reproducible builds by pinning dependencies inside your Dockerfiles [SongStitch](https://github.com/songStitch/).
* [segspec](https://github.com/dormstern/segspec) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2026-02-23 - Extracts network dependencies from Docker Compose, Kubernetes manifests, Helm charts, and other config files to generate Kubernetes NetworkPolicies with evidence tracing. By [dormstern](https://github.com/dormstern).
* [Den](https://github.com/us/den) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2026-03-15 - Self-hosted sandbox runtime for AI agents with Docker containers, security hardening, REST API and WebSocket support. By [us](https://github.com/us).
* [dvwassl](https://github.com/Peco602/dvwassl) ⭐ 6 | 🐛 0 | 🌐 Dockerfile | 📅 2023-04-30 :ice\_cube: - SSL-enabled Damn Vulnerable Web App to test Web Application Firewalls. By [Peco602][peco602].
* [buildcage](https://github.com/dash14/buildcage) ⭐ 4 | 🐛 6 | 🌐 JavaScript | 📅 2026-04-19 - Restricts outbound network access during Docker builds to prevent supply chain attacks, working as a drop-in BuildKit remote driver for Docker Buildx, with ready-to-use GitHub Actions.
* [pindock](https://github.com/deadnews/pindock) ⭐ 1 | 🐛 1 | 🌐 Go | 📅 2026-04-03 - Pin and update Docker image digests in Dockerfiles and compose files. By [deadnews](https://github.com/deadnews).
* [Anchor Enterprise](https://anchore.com/) - :yen: Analyze images for CVE vulnerabilities and against custom security policies.
* [Aqua Security](https://www.aquasec.com) - :yen: Securing container-based applications from Dev to Production on any platform.
* [Deepfence Enterprise](https://deepfence.io) - :yen: Full life cycle Cloud Native Workload Protection platform for kubernetes, virtual machines and serverless. By [deepfence][deepfence].
* [Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud) - :yen: (Previously Twistlock Security Suite) detects vulnerabilities, hardens container images, and enforces security policies across the lifecycle of applications.
* [Sysdig Secure](https://www.sysdig.com/solutions/cloud-detection-and-response-cdr) - :yen: Sysdig Secure addresses run-time security through behavioral monitoring and defense, and provides deep forensics based on open source Sysdig for incident response.
* [Trend Micro DeepSecurity](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/deep-security.html) - :yen: Trend Micro DeepSecurity offers runtime protection for container workloads and hosts as well as preruntime scanning of images to identify vulnerabilities, malware and content such as hardcoded secrets.

### Service Discovery

* [etcd](https://github.com/etcd-io/etcd) ⭐ 51,641 | 🐛 236 | 🌐 Go | 📅 2026-04-25 - Distributed reliable key-value store for the most critical data of a distributed system by [etcd-io](https://github.com/etcd-io) (former part of CoreOS).
* [istio](https://github.com/istio/istio) ⭐ 38,152 | 🐛 496 | 🌐 Go | 📅 2026-04-26 - An open platform to connect, manage, and secure microservices.
* [registrator](https://github.com/gliderlabs/registrator) ⭐ 4,674 | 🐛 259 | 🌐 Go | 📅 2025-05-22 - Service registry bridge for Docker by [gliderlabs][gliderlabs] and [progrium][progrium].
* [docker-consul](https://github.com/gliderlabs/docker-consul) ⭐ 1,062 | 🐛 34 | 🌐 Shell | 📅 2021-03-23 by [progrium][progrium]
* [docker-dns](https://github.com/bytesharky/docker-dns) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2025-12-26 - Lightweight DNS forwarder for Docker containers, resolves container names with custom suffixes (e.g. `.docker`) on the host to simplify service discovery.

### Volume Management / Data

* [Docker Volume Backup](https://github.com/offen/docker-volume-backup) ⭐ 3,524 | 🐛 26 | 🌐 Go | 📅 2026-04-21 Backup Docker volumes locally or to any S3 compatible storage. By [offen](https://github.com/offen)

* [REX-Ray](https://github.com/rexray/rexray) ⭐ 2,221 | 🐛 294 | 🌐 Go | 📅 2023-09-02 provides a vendor agnostic storage orchestration engine. The primary design goal is to provide persistent storage for Docker, Kubernetes, and Mesos. By[thecodeteam](https://github.com/thecodeteam) (DELL Technologies)

* [Netshare](https://github.com/ContainX/docker-volume-netshare) ⭐ 1,142 | 🐛 99 | 🌐 Go | 📅 2021-04-12 Docker NFS, AWS EFS, Ceph & Samba/CIFS Volume Plugin. By [ContainX][containx]

* [Blockbridge](https://github.com/blockbridge/blockbridge-docker-volume) ⭐ 94 | 🐛 0 | 🌐 Ruby | 📅 2021-06-08 :yen:- The Blockbridge plugin is a volume plugin that provides access to an extensible set of container-based persistent storage options. It supports single and multi-host Docker environments with features that include tenant isolation, automated provisioning, encryption, secure deletion, snapshots and QoS. By [blockbridge](https://github.com/blockbridge)

* * [Label Backup](https://github.com/resulgg/label-backup) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2025-10-27 - A lightweight, Docker-aware backup agent that automatically discovers and backs up containerized databases (PostgreSQL, MySQL, MongoDB, Redis) based on Docker labels. Supports local storage and S3-compatible destinations with flexible scheduling via cron expressions.

* [duplicacy-cli-cron](https://github.com/GeiserX/duplicacy-cli-cron) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-04-25 - Docker-based encrypted dual-storage backup automation using Duplicacy CLI with cross-site redundancy and Telegram notifications. By [GeiserX](https://github.com/GeiserX).

* [Storidge](https://github.com/Storidge/quick-start) ⭐ 1 | 🐛 1 | 📅 2019-09-09 :ice\_cube: - :yen: Software-defined Persistent Storage for Kubernetes and Docker Swarm.

* [portworx](https://portworx.com) - :yen: Decentralized storage solution for persistent, shared and replicated volumes.

* [quobyte](https://www.quobyte.com/) - :yen: Fully fault-tolerant distributed file system with a docker volume driver.

### User Interface

#### IDE integrations

* JetBrains IDEs (IntelliJ IDEA, GoLand, WebStorm, CLion etc.) has [built-in Docker plugin](https://www.jetbrains.com/help/idea/docker.html#managing-images)
* Eclipse [Docker Tooling plugin](https://www.eclipse.org/community/eclipse_newsletter/2016/july/article2.php)
* [docker.el](https://github.com/Silex/docker.el) ⭐ 819 | 🐛 6 | 🌐 Emacs Lisp | 📅 2026-01-26 Manage docker from Emacs by [Silex](https://github.com/Silex)

#### Desktop

Native desktop applications for managing and monitoring docker hosts and clusters

* [Simple Docker UI](https://github.com/felixgborrego/simple-docker-ui) ⭐ 605 | 🐛 20 | 🌐 Scala | 📅 2024-09-06 - Built on Electron. By [felixgborrego](https://github.com/felixgborrego/).
* [Stevedore](https://github.com/slonopotamus/stevedore) ⭐ 368 | 🐛 3 | 🌐 Rust | 📅 2026-04-13 - Good Docker Desktop replacement for Windows. Both Linux and Windows Containers are supported. [slonopotamus](https://github.com/slonopotamus).
* [Docker DB Manager](https://github.com/AbianS/docker-db-manager) ⭐ 160 | 🐛 10 | 🌐 TypeScript | 📅 2026-04-12 - Desktop app for managing Docker database containers with visual interface and one-click operations.
* [Docker Desktop](https://www.docker.com/products/docker-desktop/) - Official native app. Only for Windows and MacOS.

#### Terminal

##### Terminal UI

* [dive](https://github.com/wagoodman/dive) ⭐ 53,833 | 🐛 203 | 🌐 Go | 📅 2025-12-15 - A tool for exploring each layer in a docker image. By [wagoodman](https://github.com/wagoodman).
* [lazydocker](https://github.com/jesseduffield/lazydocker) ⭐ 50,808 | 🐛 273 | 🌐 Go | 📅 2026-04-19 - The lazier way to manage everything docker. A simple terminal UI for both docker and docker-compose, written in Go with the gocui library. By [jesseduffield](https://github.com/jesseduffield).
* [dockly](https://github.com/lirantal/dockly) ⭐ 4,014 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-01 - An interactive shell UI for managing Docker containers.
* [dry](https://github.com/moncho/dry) ⭐ 3,243 | 🐛 25 | 🌐 Go | 📅 2026-04-09 - An interactive CLI for Docker containers.
* [DockSTARTer](https://github.com/GhostWriters/DockSTARTer) ⭐ 2,555 | 🐛 8 | 🌐 Shell | 📅 2026-04-26 - DockSTARTer helps you get started with home server apps running in Docker by [GhostWriters](https://github.com/GhostWriters).
* [oxker](https://github.com/mrjackwills/oxker) ⭐ 1,630 | 🐛 20 | 🌐 Rust | 📅 2026-03-24 - A simple tui to view & control docker containers. Written in [Rust](https://rust-lang.org/), making heavy use of [ratatui](https://github.com/tui-rs-revival/ratatui) ⭐ 20,057 | 🐛 193 | 🌐 Rust | 📅 2026-04-24 & [Bollard](https://github.com/fussybeaver/bollard) ⭐ 1,262 | 🐛 47 | 🌐 Rust | 📅 2026-04-22,.
* [lazyjournal](https://github.com/Lifailon/lazyjournal) ⭐ 1,238 | 🐛 3 | 🌐 Go | 📅 2026-04-02 - A interface for reading and filtering the logs output of Docker and Podman containers like [Dozzle](origin/dozzle) but for the terminal with support for fuzzy find, regex and output coloring.
* [goManageDocker](https://github.com/ajayd-san/gomanagedocker) ⭐ 637 | 🐛 12 | 🌐 Go | 📅 2024-12-28 - TUI tool to view and manage your docker objects blazingly fast with sensible keybindings, also supports VIM navigation out of the box.
* [DockMate](https://github.com/shubh-io/dockmate) ⭐ 299 | 🐛 2 | 🌐 Go | 📅 2026-04-06 - Lightweight terminal-based Docker and Podman manager with a text-based user interface,.
* [dockdash](https://github.com/byrnedo/dockdash) ⭐ 125 | 🐛 0 | 🌐 Go | 📅 2022-06-01 detailed stats. By [byrnedo]
* [easydocker](https://github.com/joao-zanutto/easydocker) ⭐ 105 | 🐛 8 | 🌐 Go | 📅 2026-04-25 - A Terminal UI highly inpired by k9s levaraging beatiful BubbleTea graphics. By [joao-zanutto](https://github.com/joao-zanutto).
* [tdocker](https://github.com/pivovarit/tdocker) ⭐ 83 | 🐛 1 | 🌐 Go | 📅 2026-04-23 - A `docker ps` replacement for everyday container operations by [@pivovarit](https://github.com/pivovarit).
* [d4s](https://github.com/jr-k/d4s) ⭐ 73 | 🐛 0 | 🌐 Go | 📅 2026-04-20 - A fast, keyboard-driven terminal UI to manage Docker containers, Compose stacks, and Swarm services with the ergonomics of K9s.
* [dprs](https://github.com/durableprogramming/dprs) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2026-03-05 - A developer-focused TUI for managing Docker containers with real-time log streaming and container management. Built with Rust. By [durableprogramming](https://github.com/durableprogramming).
* [swarmcli](https://github.com/Eldara-Tech/swarmcli) ⭐ 14 | 🐛 10 | 🌐 Go | 📅 2026-04-25 - Swarm Management at the speed of thought — with real-time log streaming, instant shell access to containers, seamless port forwarding, and on-demand secret reveal capabilities, giving you full control over your Docker Swarm without breaking your flow.

##### CLI tools

* [skopeo](https://github.com/containers/skopeo) ⭐ 10,772 | 🐛 74 | 🌐 Go | 📅 2026-04-26 - Work with remote images registries - retrieving information, images, signing content.

* [DVM](https://github.com/howtowhale/dvm) ⭐ 527 | 🐛 16 | 🌐 Go | 📅 2022-03-30 :ice\_cube: - Docker version manager.

* [captain](https://github.com/jenssegers/captain) ⭐ 245 | 🐛 7 | 🌐 Go | 📅 2022-12-08 :ice\_cube: - Easily start and stop docker compose projects from any directory. By [jenssegers](https://github.com/jenssegers).

* [docker pushrm](https://github.com/christian-korneck/docker-pushrm) ⭐ 150 | 🐛 6 | 🌐 Go | 📅 2024-06-10 - A Docker CLI plugin that lets you push the README.md file from the current directory to Docker Hub. Also supports Quay and Harbor. By [christian-korneck](https://github.com/christian-korneck).

* [decompose](https://github.com/s0rg/decompose) ⭐ 131 | 🐛 5 | 🌐 Go | 📅 2026-04-08 - Reverse-engineering tool for docker environments. By [s0rg](https://github.com/s0rg).

* [dcp](https://github.com/exdx/dcp) ⭐ 115 | 🐛 15 | 🌐 Rust | 📅 2023-07-24 :ice\_cube: - A simple tool for copying files from container filesystems. By [exdx](https://github.com/exdx).

* [proco](https://github.com/shiwaforce/poco) ⭐ 112 | 🐛 22 | 🌐 Python | 📅 2026-02-28 - Proco will help you to organise and manage Docker, Docker-Compose, Kubernetes projects of any complexity using simple YAML config files to shorten the route from finding your project to initialising it in your local environment.

* [scuba](https://github.com/JonathonReinhart/scuba) ⭐ 98 | 🐛 29 | 🌐 Python | 📅 2026-01-26 - Transparently use Docker containers to encapsulate software build environments,.

* [supdock](https://github.com/segersniels/supdock) ⭐ 87 | 🐛 0 | 🌐 Rust | 📅 2026-04-04 - Allows for slightly more visual usage of Docker with an interactive prompt. By [segersniels](https://github.com/segersniels).

* [tsaotun](https://github.com/qazbnm456/tsaotun) ⭐ 56 | 🐛 1 | 🌐 Python | 📅 2022-10-04 :ice\_cube: - Python based Assistance for Docker.

* [goinside](https://github.com/iamsoorena/goinside) ⭐ 31 | 🐛 0 | 🌐 JavaScript | 📅 2020-10-17 :ice\_cube: - Get inside a running docker container easily.

* [dctl](https://github.com/FabienD/docker-stack) ⭐ 24 | 🐛 1 | 🌐 Rust | 📅 2026-04-14 - Dctl is a Cli tool that helps developers by allowing them to execute all docker compose commands anywhere in the terminal, and more. By [FabienD](https://github.com/FabienD).

* [dcinja](https://github.com/Falldog/dcinja) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2025-06-26 - The powerful and smallest binary size of template engine for docker command line environment. By [Falldog](https://github.com/Falldog).

* [Pdocker](https://github.com/g31s/Pdocker) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2021-02-27 :ice\_cube: - A simple tool to manage and maintain Docker for personal projects.

* [docker-captain](https://github.com/lucabello/docker-captain) ⭐ 2 | 🐛 4 | 🌐 Python | 📅 2026-04-25 - A friendly CLI to manage multiple Docker Compose deployments with style — powered by Typer, Rich, questionary, and sh.

##### Other

* [docker-ssh](https://github.com/jeroenpeeters/docker-ssh) ⭐ 659 | 🐛 30 | 🌐 JavaScript | 📅 2018-04-11 :ice\_cube: - SSH Server for Docker containers \~ Because every container should be accessible. By [jeroenpeeters](https://github.com/jeroenpeeters).

* [dockerfile-mode](https://github.com/spotify/dockerfile-mode) ⭐ 562 | 🐛 12 | 🌐 Emacs Lisp | 📅 2025-12-21 An emacs mode for handling Dockerfiles by [spotify][spotify]

* [Powerline-Docker](https://github.com/adrianmo/powerline-docker) ⭐ 62 | 🐛 2 | 🌐 Python | 📅 2017-06-30 :ice\_cube: - A Powerline segment for showing the status of Docker containers.

* [MultiDocker](https://github.com/marty90/multidocker) ⭐ 56 | 🐛 0 | 🌐 Dockerfile | 📅 2018-11-27 :ice\_cube: - Create a secure multi-user Docker machine, where each user is segregated into an indepentent container.

* [dext-docker-registry-plugin](https://github.com/vutran/dext-docker-registry-plugin) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-10 :ice\_cube: - Search the Docker Registry with the Dext smart launcher. By [vutran](https://github.com/vutran).

#### Web

* [netdata](https://github.com/netdata/netdata) ⭐ 78,603 | 🐛 292 | 🌐 C | 📅 2026-04-26 - Real-time performance monitoring.
* [Portainer](https://github.com/portainer/portainer) ⭐ 37,288 | 🐛 737 | 🌐 TypeScript | 📅 2026-04-24 - A lightweight management UI for managing your Docker hosts or Docker Swarm clusters.
* [dockge](https://github.com/louislam/dockge) ⭐ 22,994 | 🐛 141 | 🌐 TypeScript | 📅 2026-04-25 - Easy-to-use and reactive self-hosted docker compose.yaml stack-oriented manager.
* [Theia](https://github.com/eclipse-theia/theia) ⭐ 21,480 | 🐛 1,472 | 🌐 TypeScript | 📅 2026-04-25 - Extensible platform to develop full-fledged multi-language Cloud & Desktop IDE-like products with state-of-the-art web technologies.
* [Komodo](https://github.com/mbecker20/komodo) ⭐ 11,011 | 🐛 478 | 🌐 Rust | 📅 2026-04-24 - A tool to build and deploy software on many servers.
* [Arcane](https://github.com/getarcaneapp/arcane) ⭐ 5,378 | 🐛 118 | 🌐 Go | 📅 2026-04-25 - An easy and modern Docker management platform, built with everybody in mind. By [getarcaneapp](https://github.com/getarcaneapp).
* [OctoLinker](https://github.com/OctoLinker/OctoLinker) ⭐ 5,354 | 🐛 62 | 🌐 HTML | 📅 2023-10-02 :ice\_cube: - A browser extension for GitHub that makes the image name in a `Dockerfile` clickable and redirect you to the related Docker Hub page.
* [Swarmpit](https://github.com/swarmpit/swarmpit) ⭐ 3,425 | 🐛 173 | 🌐 Clojure | 📅 2026-04-22 - Swarmpit provides simple and easy to use interface for your Docker Swarm cluster. You can manage your stacks, services, secrets, volumes, networks etc.
* [docker-swarm-visualizer](https://github.com/dockersamples/docker-swarm-visualizer) ⭐ 3,352 | 🐛 11 | 🌐 JavaScript | 📅 2024-10-26 - Visualizes Docker services on a Docker Swarm (for running demos).
* [Seagull](https://github.com/tobegit3hub/seagull) ⭐ 1,935 | 🐛 20 | 🌐 JavaScript | 📅 2017-11-22 :ice\_cube: - Friendly Web UI to monitor docker daemon.
* [Kubevious](https://github.com/kubevious/kubevious) ⭐ 1,694 | 🐛 17 | 📅 2024-01-15 :ice\_cube: - A highly visual web UI for Kubernetes which renders configuration and state in an application centric way.
* [dockemon](https://github.com/ProductiveOps/dokemon) ⭐ 766 | 🐛 18 | 🌐 TypeScript | 📅 2024-02-21 :ice\_cube: - Docker Container Management GUI.
* [Mafl](https://github.com/hywax/mafl) ⭐ 695 | 🐛 45 | 🌐 TypeScript | 📅 2025-10-26 - Minimalistic flexible homepage.
* [Docker Registry Browser](https://github.com/klausmeyer/docker-registry-browser) ⭐ 685 | 🐛 9 | 🌐 Ruby | 📅 2026-04-24 - Web Interface for the Docker Registry HTTP API v2.
* [Swirl](https://github.com/cuigh/swirl) ⭐ 668 | 🐛 23 | 🌐 Go | 📅 2023-05-16 :ice\_cube: - Swirl is a web management tool for Docker, focused on swarm cluster By [cuigh](https://github.com/cuigh/).
* [docker-registry-web](https://github.com/mkuchin/docker-registry-web) ⭐ 547 | 🐛 46 | 🌐 Groovy | 📅 2022-02-08 :ice\_cube: - Web UI, authentication service and event recorder for private docker registry v2.
* [Container Web TTY](https://github.com/wrfly/container-web-tty) ⭐ 258 | 🐛 12 | 🌐 Go | 📅 2026-04-16 - Connect your containers via a web-tty [wrfly](https://github.com/wrfly).
* [Rapid Dashboard](https://github.com/ozlerhakan/rapid) ⭐ 147 | 🐛 1 | 🌐 Java | 📅 2021-09-21 :ice\_cube: - A simple query dashboard to use Docker Remote API.
* [usulnet](https://github.com/fr4nsys/usulnet) ⭐ 93 | 🐛 2 | 🌐 Go | 📅 2026-02-23 - A complete and modern Docker management platform designed for sysadmin, devops with enterprise grade tools, cve scanner, ssh, rdp on web and much more. By [fr4nsys](https://github.com/fr4nsys).
* [CASA](https://github.com/knrdl/casa) ⭐ 86 | 🐛 0 | 🌐 Svelte | 📅 2026-04-21 - Outsource the administration of a handful of containers to your co-workers,.

## Docker Images

### Base Tools

Tools and applications that are either installed inside containers or designed to be run as a [sidecar](https://learn.microsoft.com/en-us/azure/architecture/patterns/sidecar)

* [distroless](https://github.com/GoogleContainerTools/distroless) ⭐ 22,554 | 🐛 17 | 🌐 Starlark | 📅 2026-04-24 - Language focused docker images, minus the operating system,.

* [docker-alpine](https://github.com/gliderlabs/docker-alpine) ⭐ 5,704 | 🐛 123 | 🌐 Shell | 📅 2021-04-01 :ice\_cube: - A super small Docker base image *(5MB)* using Alpine Linux.

* [GoSu](https://github.com/tianon/gosu) ⭐ 4,961 | 🐛 8 | 🌐 Shell | 📅 2026-03-04 - Run this specific application as this specific user and get out of the pipeline (entrypoint script tool).

* [docker-gen](https://github.com/jwilder/docker-gen) ⭐ 4,624 | 🐛 52 | 🌐 Go | 📅 2026-04-15 - Generate files from docker container meta-data.

* [Ofelia](https://github.com/mcuadros/ofelia/) ⭐ 3,814 | 🐛 145 | 🌐 Go | 📅 2026-04-23 - Ofelia is a modern and low footprint job scheduler for docker environments, built on Go. Ofelia aims to be a replacement for the old fashioned cron. Supports configuration from container labels and/or configuration files.

* [supercronic](https://github.com/aptible/supercronic) ⭐ 2,469 | 🐛 45 | 🌐 Go | 📅 2026-04-23 - Crontab-compatible job runner, designed specifically to run in containers.

* [amicontained](https://github.com/genuinetools/amicontained) ⭐ 1,077 | 🐛 7 | 🌐 Go | 📅 2020-12-09 :ice\_cube: - Container introspection tool. Find out what container runtime is being used as well as features available.

* [su-exec](https://github.com/ncopa/su-exec) ⭐ 1,017 | 🐛 17 | 🌐 C | 📅 2025-10-07 - This is a simple tool that will simply execute a program with different privileges. The program will be executed directly and not run as a child, like su and sudo does, which avoids TTY and signal issues. Why reinvent gosu? This does more or less exactly the same thing as gosu but it is only 10kb instead of 1.8MB. By [ncopa](https://github.com/ncopa).

* [lstags](https://github.com/ivanilves/lstags) ⭐ 343 | 🐛 10 | 🌐 Go | 📅 2023-05-11 :ice\_cube: - Sync Docker images across registries.

* [is-docker](https://github.com/sindresorhus/is-docker) ⭐ 233 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-15 - Check if the process is running inside a Docker container.

* [dockerize](https://github.com/powerman/dockerize) ⭐ 195 | 🐛 7 | 🌐 Go | 📅 2026-04-21 - Utility to simplify running applications in docker containers by [jwilder][jwilder], [powerman][powerman].

* [Chaperone](https://github.com/garywiz/chaperone) ⭐ 178 | 🐛 19 | 🌐 Python | 📅 2020-07-16 :ice\_cube: - A single PID1 process designed for docker containers. Does user management, log management, startup, zombie reaping, all in one small package.

* [microcheck](https://github.com/tarampampam/microcheck) ⭐ 137 | 🐛 0 | 🌐 C | 📅 2026-04-24 - Lightweight health check utilities for Docker containers (75 KB instead of 9.3 MB for httpcheck versus cURL) in pure C - http(s), port checks, and parallel execution are included.

* [ckron](https://github.com/nicomt/ckron) ⭐ 56 | 🐛 21 | 🌐 JavaScript | 📅 2026-02-15 - A cron-style job scheduler for docker,.

* [TrivialRC](https://github.com/vorakl/TrivialRC) ⭐ 32 | 🐛 0 | 🌐 Shell | 📅 2023-12-20 :ice\_cube: - A minimalistic Runtime Configuration system and process manager for containers [vorakl](https://github.com/vorakl).

* [SparkView](https://github.com/beyondssl/sparkview-container) ⭐ 20 | 🐛 1 | 🌐 HTML | 📅 2025-09-22 - Access VMs, desktops, servers or applications anytime and from anywhere, without complex and costly client roll-outs or user management.

* [sue](https://github.com/theAkito/sue) ⭐ 13 | 🐛 0 | 🌐 Nim | 📅 2022-04-26 :ice\_cube: - Executes a program as a user different from the user running sue. This is a maintainable alternative to ncopa/su-exec, which is the better tianon/gosu. This one is far better (higher performance, smaller size), than the original gosu, however it is far easier to maintain, than su-exec, which is written in plain C. Made by [Akito][akito].

* [CoreOS][coreos] - Linux for Massive Server Deployments

### Builder

Applications designed to help or simplify building **new** images

* [DockerSlim](https://github.com/docker-slim/docker-slim) ⭐ 23,164 | 🐛 208 | 🌐 Go | 📅 2026-04-16 shrinks fat Docker images creating the smallest possible images.

* [BuildKit](https://github.com/moby/buildkit) ⭐ 9,927 | 🐛 909 | 🌐 Go | 📅 2026-04-24 - Concurrent, cache-efficient, and Dockerfile-agnostic builder toolkit.

* [buildah](https://github.com/containers/buildah) ⭐ 8,752 | 🐛 247 | 🌐 Go | 📅 2026-04-24 - A tool that facilitates building OCI images.

* [img](https://github.com/genuinetools/img) ⭐ 3,982 | 🐛 110 | 🌐 Go | 📅 2024-05-19 - Standalone, daemon-less, unprivileged Dockerfile and OCI compatible container image builder.

* [runlike](https://github.com/lavie/runlike) ⭐ 2,925 | 🐛 8 | 🌐 Python | 📅 2025-12-04 - Generate `docker run`command and options from running containers.

* [Whaler](https://github.com/P3GLEG/Whaler) ⭐ 1,184 | 🐛 7 | 🌐 Go | 📅 2026-04-08 - Program to reverse Docker images into Dockerfiles.

* [ansible-bender](https://github.com/ansible-community/ansible-bender) ⭐ 696 | 🐛 45 | 🌐 Python | 📅 2026-01-07 - A tool utilising `ansible` and `buildah`.

* [Derrick](https://github.com/alibaba/derrick) ⭐ 693 | 🐛 11 | 🌐 Go | 📅 2023-03-06 :ice\_cube: - A tool help you to automate the generation of Dockerfile and dockerize application by scanning the code. By [alibaba](https://github.com/alibaba).

* [RAUDI](https://github.com/cybersecsi/RAUDI) ⭐ 561 | 🐛 5 | 🌐 Python | 📅 2026-04-25 - A tool to automatically update (and optionally push to Docker Hub) Docker Images for 3rd party software whenever theres is a new release/update/commit. By [SecSI](https://github.com/cybersecsi).

* [HPC Container Maker](https://github.com/NVIDIA/hpc-container-maker) ⭐ 512 | 🐛 19 | 🌐 Python | 📅 2026-04-17 - Generates Dockerfiles from a high level Python recipe, including building blocks for High-Performance Computing components.

* [dlayer](https://github.com/orisano/dlayer) ⭐ 446 | 🐛 6 | 🌐 Go | 📅 2026-04-20 - Docker layer analyzer.

* [Whales](https://github.com/Gueils/whales) ⭐ 393 | 🐛 4 | 🌐 Ruby | 📅 2019-05-27 :ice\_cube: - A tool to automatically dockerize your applications.

* [Dockly](https://github.com/swipely/dockly) ⭐ 228 | 🐛 2 | 🌐 Ruby | 📅 2023-02-15 :ice\_cube: - Dockly is a gem made to ease the pain of packaging an application in Docker.

* [docker-replay](https://github.com/bcicen/docker-replay) ⭐ 202 | 🐛 0 | 🌐 Python | 📅 2018-10-13 :ice\_cube: - Generate `docker run`command and options from running containers. By [bcicen](https://github.com/bcicen).

* [docker-repack](https://github.com/orf/docker-repack) ⭐ 152 | 🐛 7 | 🌐 Rust | 📅 2025-04-24 - Repacks a Docker image into a smaller, more efficient version that makes it significantly faster to pull. By [orf](https://github.com/orf).

* [portainer](https://github.com/duedil-ltd/portainer) ⭐ 134 | 🐛 14 | 🌐 Python | 📅 2017-02-28 :ice\_cube: - Apache Mesos framework for building Docker images.

* [cekit](https://github.com/cekit/cekit) ⭐ 113 | 🐛 30 | 🌐 Python | 📅 2026-03-30 - A tool used by openshift to build base images using different build engines.

* [docker-make](https://github.com/CtripCloud/docker-make) ⭐ 99 | 🐛 3 | 🌐 Python | 📅 2019-11-22 :ice\_cube: - Build, tag,and push a bunch of related docker images via a single command.

* [container-factory](https://github.com/mutable/container-factory) ⭐ 64 | 🐛 0 | 🌐 Go | 📅 2015-05-06 :ice\_cube: - Produces Docker images from tarballs of application source code.

* [docker-companion](https://github.com/mudler/docker-companion) ⭐ 47 | 🐛 5 | 🌐 Go | 📅 2025-05-28 - A command line tool written in Golang to squash and unpack docker images.

* [copy-docker-image](https://github.com/mdlavin/copy-docker-image) ⭐ 38 | 🐛 4 | 🌐 Go | 📅 2018-08-29 :ice\_cube: - Copy a Docker image between registries without a full Docker installation.

* [essex](https://github.com/utensils/essex) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2025-03-18 - Boilerplate for Docker Based Projects: Essex is a CLI utility written in bash to quickly setup clean and consistent Docker projects with Makefile driven workflows. [jamesbrink](https://github.com/jamesbrink).

* [userdef](https://github.com/theAkito/userdef) ⭐ 11 | 🐛 0 | 🌐 Nim | 📅 2023-10-14 :ice\_cube: - An advanced `adduser` for your Alpine based Docker images. Made by [Akito][akito].

* [packer](https://developer.hashicorp.com/packer/integrations/hashicorp/docker/latest/components/builder/docker) - Hashicorp tool to build machine images including docker image integrated with configuration management tools like chef, puppet, ansible.

* [Production-Ready Python Containers :yen:](https://pythonspeed.com/products/pythoncontainer/) - A template for creating production-ready Docker images for Python applications.

### Dockerfile

* [dockerfilegraph](https://github.com/patrickhoefler/dockerfilegraph) ⭐ 263 | 🐛 0 | 🌐 Go | 📅 2026-04-20 - Visualize your multi-stage Dockerfiles. By [PatrickHoefler](https://github.com/patrickhoefler).
* [Dockerfile Generator](https://github.com/ozankasikci/dockerfile-generator) ⭐ 185 | 🐛 0 | 🌐 Go | 📅 2022-05-23 `dfg` is both a Go library and an executable that produces valid Dockerfiles using various input channels.
* [Dockershelf](https://github.com/Dockershelf/dockershelf) ⭐ 96 | 🐛 1 | 🌐 Shell | 📅 2026-04-16 - A repository that serves as a collector for docker recipes that are universal, efficient and slim. Images are updated, tested and published daily via a Travis cron job.
* [chaperone-docker](https://github.com/garywiz/chaperone-docker) ⭐ 66 | 🐛 5 | 🌐 JavaScript | 📅 2018-10-05 :ice\_cube: - A set of images using the Chaperone process manager, including a lean Alpine image, LAMP, LEMP, and bare-bones base kits.
* [Dockerfile Project](https://dockerfile.github.io/) - Trusted Automated Docker Builds. Dockerfile Project maintains a central repository of Dockerfile for various popular open source software services runnable on a Docker container.
* [Vektorcloud](https://github.com/vektorcloud) - A collection of minimal, Alpine-based Docker images.

Examples by:

* [jessfraz](https://github.com/jessfraz/dockerfiles) ⭐ 13,943 | 🐛 79 | 🌐 Dockerfile | 📅 2024-07-06
* [vimagick](https://github.com/vimagick/dockerfiles) ⭐ 3,203 | 🐛 82 | 🌐 Dockerfile | 📅 2026-02-23
* [kstaken](https://github.com/kstaken/dockerfile-examples) ⭐ 827 | 🐛 5 | 🌐 Shell | 📅 2019-10-24
* [komljen](https://github.com/komljen/dockerfile-examples) ⭐ 586 | 🐛 0 | 🌐 Shell | 📅 2016-09-09
* [crosbymichael](https://github.com/crosbymichael/Dockerfiles) ⭐ 300 | 🐛 0 | 🌐 Python | 📅 2017-04-25
* [arun-gupta](https://github.com/arun-gupta/docker-images) ⭐ 251 | 🐛 13 | 🌐 Shell | 📅 2025-10-16
* [awesome-startup](https://github.com/awesome-startup/docker-compose) ⭐ 65 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-08
* [ondrejmo](https://github.com/ondrejmo/Dockerfiles) ⭐ 23 | 🐛 0 | 🌐 Dockerfile | 📅 2020-05-27
* [0xy](https://gitlab.com/0xy/dockerfiles)

### Linter

* [Hadolint](https://github.com/hadolint/hadolint) ⭐ 12,079 | 🐛 257 | 🌐 Haskell | 📅 2026-04-23 - A Dockerfile linter that checks for best practices, common mistakes, and is also able to lint any bash written in `RUN` instructions;.
* [FROM:latest](https://github.com/replicatedhq/dockerfilelint) ⭐ 1,031 | 🐛 55 | 🌐 JavaScript | 📅 2023-09-27 :ice\_cube: - An opinionated Dockerfile linter.
* [Dockadvisor](https://github.com/deckrun/dockadvisor) ⭐ 201 | 🐛 0 | 🌐 Go | 📅 2026-01-12 - Lightweight Dockerfile linter with 60+ rules, quality scoring, and security checks.
* [docker-image-size-limit](https://github.com/wemake-services/docker-image-size-limit) ⭐ 131 | 🐛 1 | 🌐 Python | 📅 2026-04-22 - A tool to keep an eye on your docker images size.
* [Dockerfile Linter action](https://github.com/buddy-works/dockerfile-linter) ⭐ 46 | 🐛 4 | 🌐 JavaScript | 📅 2023-03-04 :ice\_cube: - The linter lets you verify Dockerfile syntax to make sure it follows the best practices for building efficient Docker images.

### Metadata

* [opencontainer](https://github.com/opencontainers/image-spec/blob/main/annotations.md) ⭐ 4,237 | 🐛 77 | 🌐 Go | 📅 2026-02-26 - A convention and shared namespace for Docker labels defined by OCI Image Spec.

### Registry

Services to securely store your Docker images.

* [Harbor](https://github.com/goharbor/harbor) ⭐ 28,349 | 🐛 845 | 🌐 Go | 📅 2026-04-24 An open source trusted cloud native registry project that stores, signs, and scans content. Supports replication, user management, access control and activity auditing. By [CNCF](https://www.cncf.io) formerly [VMWare][vmware]
* [Kraken](https://github.com/uber/kraken) ⭐ 6,683 | 🐛 124 | 🌐 Go | 📅 2026-04-24 - Uber's Highly scalable P2P docker registry, capable of distributing TBs of data in seconds.
* [Dragonfly](https://github.com/dragonflyoss/Dragonfly2) ⭐ 3,147 | 🐛 33 | 🌐 Go | 📅 2026-04-23 - Provide efficient, stable and secure file distribution and image acceleration based on p2p technology.
* [Docket](https://github.com/netvarun/docket) ⭐ 709 | 🐛 4 | 🌐 Go | 📅 2020-09-02 :ice\_cube: - Custom docker registry that allows for lightning fast deploys through bittorrent.
* [NORA](https://github.com/getnora-io/nora) ⭐ 128 | 🐛 15 | 🌐 Rust | 📅 2026-04-23 - Lightweight multi-protocol artifact registry supporting Docker, Maven, npm, Cargo and PyPI in a single 32MB binary. Pull-through cache, Web UI, Prometheus metrics, RBAC auth.
* [cleanreg](https://github.com/hcguersoy/cleanreg) ⭐ 59 | 🐛 2 | 🌐 Shell | 📅 2022-09-03 :ice\_cube: - A small tool to delete image manifests from a Docker Registry implementing the API v2, dereferencing them for the GC.
* [Rescoyl](https://github.com/noteed/rescoyl) ⭐ 18 | 🐛 0 | 🌐 Haskell | 📅 2017-04-08 :ice\_cube: - Private Docker registry (free and open source).
* [Registryo](https://github.com/inmagik/registryo) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2025-12-17 - UI and token based authentication server for onpremise docker registry.
* [CargoOS](https://github.com/RedCoolBeans/cargos-buildroot) ⭐ 12 | 🐛 2 | 🌐 Makefile | 📅 2017-04-02 :ice\_cube: - A bare essential OS for running the Docker Engine on bare metal or Cloud. By [RedCoolBeans](https://github.com/RedCoolBeans).
* [nscr](https://github.com/jhstatewide/nscr) ⭐ 1 | 🐛 1 | 🌐 Kotlin | 📅 2025-10-27 - A light-weight, self-contained container registry that's easy to run and maintain.
* [Amazon Elastic Container Registry :yen:](https://aws.amazon.com/ecr/) - Amazon Elastic Container Registry (ECR) is a fully-managed Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images.
* [Azure Container Registry :yen:](https://azure.microsoft.com/en-us/products/container-registry/#overview) - Manage a Docker private registry as a first-class Azure resource.
* [Cloudsmith :yen:](https://cloudsmith.com/product/formats/docker-registry) - A fully managed package management SaaS, with first-class support for public and private Docker registries (and many others, incl. Helm charts for the Kubernetes ecosystem). Has a generous free-tier and is also completely free for open-source.
* [Container Registry Service :yen:](https://container-registry.com/) - Harbor based Container Management Solution as a Service for teams and organizations. Free tier offers 1 GB storage for private repositories.
* [Cycle.io :yen:](https://cycle.io/) - Bare-metal container hosting.
* [DigitalOcean :yen:](https://www.digitalocean.com/products/container-registry) - DigitalOcean Container Registry.
* [Docker Hub](https://hub.docker.com/) provided by Docker Inc.
* [Docker Registry v2][distribution] - The Docker toolset to pack, ship, store, and deliver content
* [GCP Artifact Registry :yen:](https://cloud.google.com/artifact-registry/docs) Fast, private Docker image storage on Google Cloud Platform.
* [Gitea Container Registry](https://docs.gitea.com/usage/packages/container) - Integrated Docker registry in Gitea, ideal for private, small-scale image hosting.
* [GitHub Container Registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry) - GitHub's solution for storing and managing Docker images, with tight integration into GitHub Actions.
* [GitLab Container Registry](https://docs.gitlab.com/user/packages/container_registry/) - Registry focused on using its images in GitLab CI.
* [JFrog Artifactory :yen:](https://jfrog.com/artifactory/) - Artifact Repository Manager, can be used as private Docker Registry as well.
* [Quay.io :yen:](https://quay.io/) - Secure hosting for private Docker repositories.
* [RepoFlow](https://www.repoflow.io) - A simple and easy-to-use package management platform with Docker support alongside other formats like PyPI, Maven, npm, and Helm. Includes smart search, built-in Docker image scanning, and a great free option for both self-hosted and cloud use.
* [Sonatype Nexus Repository](https://www.sonatype.com/products/sonatype-nexus-repository) - Manage binaries and build artifacts across your software supply chain.

## Development with Docker

### API Client

* [dockerode](https://github.com/apocas/dockerode) ⭐ 4,875 | 🐛 24 | 🌐 JavaScript | 📅 2026-04-23 - Docker Remote API node.js module.
* [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) ⭐ 2,410 | 🐛 188 | 🌐 C# | 📅 2025-08-28 - C#/.NET HTTP client for the Docker remote API.
* [go-dockerclient](https://github.com/fsouza/go-dockerclient/) ⭐ 2,234 | 🐛 15 | 🌐 Go | 📅 2026-04-21 - Go HTTP client for the Docker remote API.
* [docker-maven-plugin](https://github.com/fabric8io/docker-maven-plugin) ⭐ 1,928 | 🐛 517 | 🌐 Java | 📅 2026-04-01 - A Maven plugin for running and creating Docker images.
* [sbt-docker](https://github.com/marcuslonnberg/sbt-docker) ⭐ 733 | 🐛 34 | 🌐 Scala | 📅 2024-12-12 - Create Docker images directly from sbt.
* [docker-it-scala](https://github.com/whisklabs/docker-it-scala) ⭐ 433 | 🐛 27 | 🌐 Scala | 📅 2024-02-14 :ice\_cube: - Docker integration testing kit with Scala.
* [docker-java-api](https://github.com/amihaiemil/docker-java-api) ⭐ 275 | 🐛 25 | 🌐 Java | 📅 2021-06-04 :ice\_cube: - Lightweight, truly object-oriented, Java client for Docker's API. By [amihaiemil](https://github.com/amihaiemil).
* [docker-controller-bot](https://github.com/dgongut/docker-controller-bot) ⭐ 245 | 🐛 11 | 🌐 Python | 📅 2026-02-04 - Telegram bot to control docker containers. By [dgongut](https://github.com/dgongut/).
* [contajners](https://github.com/lispyclouds/contajners) ⭐ 148 | 🐛 0 | 🌐 Clojure | 📅 2026-04-14 - An idiomatic, data-driven, REPL friendly Clojure client for OCI container engines. By [lispyclouds][lispyclouds].
* [ahab](https://github.com/instacart/ahab) ⭐ 139 | 🐛 1 | 🌐 Python | 📅 2018-11-16 :ice\_cube: - Docker event handling with Python.
* [Docker Client for JVM](https://github.com/gesellix/docker-client) ⭐ 120 | 🐛 27 | 🌐 Groovy | 📅 2026-04-23 - A Docker remote api client library for the JVM, written in Groovy.
* [Gradle Docker plugin](https://github.com/gesellix/gradle-docker-plugin) ⭐ 82 | 🐛 17 | 🌐 Java | 📅 2026-04-24 - A Docker remote api plugin for Gradle.
* [DoMonit](https://github.com/eon01/DoMonit) ⭐ 76 | 🐛 5 | 🌐 Python | 📅 2021-06-01 :ice\_cube: - A simple Docker Monitoring wrapper For Docker API.
* [Portainer stack utils](https://github.com/greenled/portainer-stack-utils) ⭐ 74 | 🐛 14 | 🌐 Go | 📅 2025-12-05 - Bash script to deploy/update/undeploy Docker stacks in a Portainer instance from a docker-compose yaml file. By [greenled](https://github.com/greenled).
* [Docker.Registry.DotNet](https://github.com/ChangemakerStudios/Docker.Registry.DotNet) ⭐ 42 | 🐛 6 | 🌐 C# | 📅 2025-10-06 - .NET (C#) Client Library for interacting with a Docker Registry API (v2) [rquackenbush](https://github.com/rquackenbush).
* [Docker Client TypeScript](https://gitlab.com/masaeedu/docker-client) - Docker API client for JavaScript, automatically generated from Swagger API definition from moby repository. By [masaeedu](https://github.com/masaeedu).

### CI/CD

* [Drone](https://github.com/drone/drone) ⭐ 35,229 | 🐛 88 | 🌐 Go | 📅 2026-04-24 - Continuous integration server built on Docker and configured using YAML files.
* [Diun](https://github.com/crazy-max/diun) ⭐ 4,607 | 🐛 105 | 🌐 Go | 📅 2026-04-24 - Receive notifications when an image or repository is updated on a Docker registry by [crazy-max].
* [dockcheck](https://github.com/mag37/dockcheck) ⭐ 2,297 | 🐛 12 | 🌐 Shell | 📅 2026-04-21 - A script checking updates for docker images without pulling then auto-update selected/all containers. With notifications, pruning and more.
* [Cyclone](https://github.com/caicloud/cyclone) ⭐ 1,070 | 🐛 44 | 🌐 Go | 📅 2023-10-24 :ice\_cube: - Powerful workflow engine and end-to-end pipeline solutions implemented with native Kubernetes resources.
* [mu](https://github.com/stelligent/mu) ⭐ 965 | 🐛 89 | 🌐 Go | 📅 2020-06-18 :ice\_cube: - Tool to configure CI/CD of your container applications via AWS CodePipeline, CodeBuild and ECS [Stelligent](https://github.com/stelligent).
* [Captain](https://github.com/harbur/captain) ⭐ 777 | 🐛 21 | 🌐 Go | 📅 2025-05-25 - Convert your Git workflow to Docker containers ready for Continuous Delivery.
* [Docker plugin for Jenkins](https://github.com/jenkinsci/docker-plugin/) ⭐ 498 | 🐛 73 | 🌐 Java | 📅 2026-04-01 - The aim of the docker plugin is to be able to use a docker host to dynamically provision a slave, run a single build, then tear-down that slave.
* [Popper](https://github.com/systemslab/popper) ⭐ 308 | 🐛 23 | 🌐 Python | 📅 2022-03-29 :ice\_cube: - Github actions workflow (HCL syntax) execution engine.
* [Kraken CI](https://github.com/Kraken-CI/kraken) ⭐ 160 | 🐛 96 | 🌐 Python | 📅 2026-01-15 - Modern CI/CD, open-source, on-premise system that is highly scalable and focused on testing. One of its executors is Docker. Developed.
* [Defang](https://github.com/DefangLabs/defang) ⭐ 152 | 🐛 207 | 🌐 Go | 📅 2026-04-25 - Deploy Docker Compose to your favorite cloud in minutes.
* [Microservices Continuous Deployment](https://github.com/francescou/docker-continuous-deployment) ⭐ 146 | 🐛 0 | 🌐 HTML | 📅 2017-08-01 :ice\_cube: - Continuous deployment of a microservices application.
* [Gantry](https://github.com/shizunge/gantry) ⭐ 88 | 🐛 0 | 🌐 Shell | 📅 2026-04-21 - Automatically update selected Docker swarm services.
* [SwarmCI](https://github.com/ghostsquad/swarmci) ⭐ 58 | 🐛 3 | 🌐 Python | 📅 2017-02-24 :ice\_cube: - Create a distributed, isolated task pipeline in your Docker Swarm.
* [Skipper](https://github.com/Stratoscale/skipper) ⭐ 50 | 🐛 5 | 🌐 Python | 📅 2025-05-13 - Easily dockerize your Git repository.
* [Jaypore CI](https://github.com/theSage21/jaypore_ci) ⭐ 38 | 🐛 1 | 🌐 Go | 📅 2026-03-07 - Simple, very flexible, powerful CI / CD / automation system configured in Python. Offline and local first.
* [Buddy :yen:](https://buddy.works) - The best of Git, build & deployment tools combined into one powerful tool that supercharged our development.
* [Depot :yen:](https://depot.dev) - Build Docker images fast, in the cloud. Blazing fast compute, automatic intelligent caching, and zero configuration. [Done in seconds](https://depot.dev/#benchmarks).
* [GitLab Runner](https://gitlab.com/gitlab-org/gitlab-runner) - GitLab has integrated CI to test, build and deploy your code with the use of GitLab runners.
* [Screwdriver :yen:](https://screwdriver.cd/) - Yahoo's OpenSource buildplatform designed for Continous Delivery.
* [Tekton CD](https://tekton.dev/) - A cloud-native pipeline resource.

### Development Environment

* [Bytebase](https://github.com/bytebase/bytebase) ⭐ 13,932 | 🐛 152 | 🌐 Go | 📅 2026-04-24 - Database DevOps and CI/CD for MySQL, PostgreSQL, and more, with SQL review, schema migration, and access control. By [Bytebase](https://github.com/bytebase).
* [coder](https://github.com/coder/coder) ⭐ 13,015 | 🐛 965 | 🌐 Go | 📅 2026-04-26 - Remote development machines powered by Terraform or Docker.
* [Eclipse Che](https://github.com/eclipse/che) ⭐ 7,163 | 🐛 265 | 🌐 TypeScript | 📅 2026-04-22 - Developer workspace server with Docker runtimes, cloud IDE, next-generation Eclipse IDE.
* [Lando](https://github.com/lando/lando) ⭐ 4,229 | 🐛 178 | 📅 2026-04-14 - Lando is for developers who want to quickly specify and painlessly spin up the services and tools needed to develop their projects. By [Tandem](https://www.thinktandem.io/).
* [Docker-sync](https://github.com/EugenMayer/docker-sync) ⭐ 3,563 | 🐛 5 | 🌐 Ruby | 📅 2025-11-30 - Drastically improves performance ([50-70x](https://github.com/EugenMayer/docker-sync/wiki/4.-Performance) ⭐ 3,563 | 🐛 5 | 🌐 Ruby | 📅 2025-11-30) when using Docker for development on Mac OS X/Windows and Linux while sharing code to the container. By [EugenMayer](https://github.com/EugenMayer).
* [Vagga](https://github.com/tailhook/vagga) ⭐ 1,897 | 🐛 78 | 🌐 Rust | 📅 2023-03-31 :ice\_cube: - Vagga is a containerisation tool without daemons. It is a fully-userspace container engine inspired by Vagrant and Docker, specialized for development environments.
* [DIP](https://github.com/bibendi/dip) ⭐ 1,328 | 🐛 15 | 🌐 Ruby | 📅 2024-12-25 - CLI utility for straightforward provisioning and interacting with an application configured by docker-compose. By [bibendi](https://github.com/bibendi).
* [Zsh-in-Docker](https://github.com/deluan/zsh-in-docker) ⭐ 1,105 | 🐛 9 | 🌐 Shell | 📅 2024-09-30 - Install Zsh, Oh-My-Zsh and plugins inside a Docker container with one line! By [Deluan](https://www.deluan.com).
* [Binci](https://github.com/binci/binci) ⭐ 673 | 🐛 16 | 🌐 JavaScript | 📅 2022-12-06 :ice\_cube: - Containerize your development workflow. (formerly DevLab by [TechnologyAdvice](https://github.com/TechnologyAdvice)).
* [Gebug](https://github.com/moshebe/gebug) ⭐ 634 | 🐛 14 | 🌐 Go | 📅 2026-04-15 - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
* [dobi](https://github.com/dnephin/dobi) ⭐ 315 | 🐛 63 | 🌐 Go | 📅 2023-11-10 :ice\_cube: - A build automation tool for Docker applications. By [dnephin](https://github.com/dnephin).
* [EnvCLI](https://github.com/EnvCLI/EnvCLI) ⭐ 116 | 🐛 4 | 🌐 Go | 📅 2025-06-16 - Replace your local installation of Node, Go, ... with project-specific docker containers. By [EnvCLI](https://github.com/EnvCLI).
* [DockerDL](https://github.com/matifali/dockerdl) ⭐ 86 | 🐛 0 | 🌐 Dockerfile | 📅 2026-03-09 - Deep Learning Docker Images. Don't waste time setting up a deep learning env when you can get a deep learning environment with everything pre-installed.
* [ESP32 Linux - Docker builder](https://github.com/hpsaturn/esp32s3-linux) ⭐ 81 | 🐛 1 | 🌐 Dockerfile | 📅 2025-04-05 - Container solution to compile Linux and develop it for ESP32 microcontrollers - By [Hpsaturn](https://github.com/hpsaturn).
* [dde](https://github.com/whatwedo/dde) ⭐ 46 | 🐛 19 | 🌐 Shell | 📅 2026-04-22 - Local development environment toolset based on Docker. By [whatwedo](https://github.com/whatwedo).
* [docker-vm](https://github.com/shyiko/docker-vm) ⭐ 43 | 🐛 2 | 🌐 Shell | 📅 2016-09-24 :ice\_cube: - Simple and transparent alternative to boot2docker (backed by Vagrant).
* [Rust Universal Compiler](https://github.com/Peco602/rust-universal-compiler) ⭐ 33 | 🐛 2 | 🌐 Dockerfile | 📅 2023-04-30 :ice\_cube: - Container solution to compile Rust projects for Linux, macOS and Windows. By [Peco602][peco602].
* [Docker-Arch](https://github.com/Ph3nol/Docker-Arch) ⭐ 31 | 🐛 3 | 🌐 PHP | 📅 2018-09-24 :ice\_cube: - Generate Web/CLI projects Dockerized development environments, from 1 simple YAML file. By [Ph3nol](https://github.com/ph3nol).
* [Docker Missing Tools](https://github.com/nandoquintana/docker-missing-tools) ⭐ 30 | 🐛 0 | 🌐 Shell | 📅 2018-05-01 :ice\_cube: - A set of bash commands to shortcut typical docker dev-ops. An alternative to creating typical helper scripts like "build.sh" and "deploy.sh" inside code repositories. By [NandoQuintana](https://github.com/nandoquintana).
* [construi](https://github.com/lstephen/construi) ⭐ 25 | 🐛 6 | 🌐 Python | 📅 2022-12-08 :ice\_cube: - Run your builds inside a Docker defined environment.
* [Kitt](https://github.com/senges/kitt) ⭐ 20 | 🐛 3 | 🌐 Python | 📅 2026-04-22 :ice\_cube: - A portable and disposable Shell environment, based on Docker and Nix. By [senges](https://github.com/senges).
* [uniget](https://github.com/uniget-org/cli) ⭐ 20 | 🐛 18 | 🌐 Go | 📅 2026-04-21 - Uni(versal)get, the installer and updater for container tools and beyond (formerly docker-setup). By [nicholasdille](https://github.com/nicholasdille).
* [HarborPilot](https://github.com/potterwhite/HarborPilot) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2026-04-23 - Automated multi-platform Docker image builder for embedded Linux development (RK3588, RV1126, RK3568). Features three-layer config inheritance, PORT\_SLOT-based port allocation, and cross-version Ubuntu support (20.04/22.04/24.04). By [potterwhite](https://github.com/potterwhite).

### Garbage Collection

* [Docker Clean](https://github.com/ZZROTDesign/docker-clean) ⭐ 1,300 | 🐛 10 | 🌐 Shell | 📅 2018-01-16 :ice\_cube: - A script that cleans Docker containers, images and volumes.
* [Docuum](https://github.com/stepchowfun/docuum) ⭐ 691 | 🐛 14 | 🌐 Rust | 📅 2026-04-26 - Least recently used (LRU) eviction of Docker images.
* [docker-custodian](https://github.com/Yelp/docker-custodian) ⭐ 374 | 🐛 15 | 🌐 Python | 📅 2026-04-02 - Keep docker hosts tidy. By [Yelp](https://github.com/Yelp).
* [docker\_gc](https://github.com/pdacity/docker_gc) ⭐ 131 | 🐛 0 | 🌐 Shell | 📅 2024-02-09 :ice\_cube: - Image for automatic removing unused Docker Swarm objects. Also works just as Docker Service.
* [caduc](https://github.com/tjamet/caduc) ⭐ 21 | 🐛 32 | 🌐 Python | 📅 2019-01-07 :ice\_cube: - A docker garbage collector cleaning stuff you did not use recently.

### Serverless

* [OpenFaaS](https://github.com/openfaas/faas) ⭐ 26,143 | 🐛 31 | 🌐 Go | 📅 2026-04-01 - A complete serverless functions framework for Docker and Kubernetes. By [OpenFaaS](https://github.com/openfaas).

* [Apache OpenWhisk](https://github.com/apache/openwhisk) ⭐ 6,767 | 🐛 435 | 🌐 Scala | 📅 2026-04-09 - A serverless, open source cloud platform that executes functions in response to events at any scale. By [apache](https://github.com/apache).

* [IronFunctions](https://github.com/iron-io/functions) ⭐ 3,218 | 🐛 94 | 🌐 Go | 📅 2023-09-15 :ice\_cube: - The serverless microservices platform FaaS (Functions as a Service) which uses Docker containers to run Any language or AWS Lambda functions.

* [SCAR](https://github.com/grycap/scar) ⭐ 600 | 🐛 28 | 🌐 Python | 📅 2023-05-22 :ice\_cube: - Serverless Container-aware Architectures (SCAR) is a serverless framework that allows easy deployment and execution of containers (e.g. Docker) in Serverless environments (e.g. Lambda).

* [Funker](https://github.com/bfirsh/funker-example-voting-app) ⭐ 26 | 🐛 0 | 🌐 JavaScript | 📅 2016-11-29 :ice\_cube: - Functions as Docker containers example voting app. By [bfirsh](https://github.com/bfirsh).

* [Koyeb](https://www.koyeb.com/) - :yen: Koyeb is a developer-friendly serverless platform to deploy apps globally. Seamlessly run Docker containers, web apps, and APIs with git-based deployment, native autoscaling, a global edge network, and built-in service mesh and discovery.

### Testing

* [dgoss](https://github.com/goss-org/goss/tree/master/extras/dgoss) ⭐ 5,888 | 🐛 99 | 🌐 Go | 📅 2025-05-01 - A fast YAML based tool for validating docker containers.
* [Pumba](https://github.com/alexei-led/pumba) ⭐ 3,013 | 🐛 12 | 🌐 Go | 📅 2026-04-24 - Chaos testing tool for Docker. Can be deployed on kubernetes and CoreOS cluster. By [alexei-led](https://github.com/alexei-led).
* [Container Structure Test](https://github.com/GoogleContainerTools/container-structure-test) ⭐ 2,471 | 🐛 113 | 🌐 Go | 📅 2026-04-15 - A framework to validate the structure of an image by checking the outputs of commands or the contents of the filesystem. By [GoogleContainerTools][googlecontainertools].
* [Kurtosis](https://github.com/kurtosis-tech/kurtosis) ⭐ 538 | 🐛 289 | 🌐 Go | 📅 2026-04-25 - A composable build system for multi-container test environments that provides developers with: a powerful Python-like SDK for environment configuration, a compile-time validator to verify environment behavior & setup, and a runtime for environment execution, monitoring, & debugging capabilities. By [Kurtosis](https://www.kurtosis.com/).
* [DockerSpec](https://github.com/zuazo/dockerspec) ⭐ 182 | 🐛 10 | 🌐 Ruby | 📅 2017-08-30 :ice\_cube: - A small Ruby Gem to run RSpec and Serverspec, Infrataster and Capybara tests against Dockerfiles or Docker images easily. By [zuazo](https://github.com/zuazo).
* [EZDC](https://github.com/lynchborg/ezdc) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2024-02-12 :ice\_cube: - Golang test harness for easily setting up tests that rely on services in a docker-compose.yml. By [byrnedo].
* [InSpec][inspec] - InSpec is an open-source testing framework for infrastructure with a human- and machine-readable language for specifying compliance, security and policy requirements. By [chef](https://github.com/chef)
* [Pull Dog](https://github.com/apps/pull-dog) - A GitHub app that automatically creates Docker-based test environments for your pull requests, from your docker-compose files. Not open source.

### Wrappers

* [Preevy](https://github.com/livecycle/preevy) ⭐ 2,203 | 🐛 51 | 🌐 TypeScript | 📅 2026-02-06 - Preview environments for Docker and Docker Compose projects. Test your changes and get feedback from devs and non-devs (Product/Design) by deploying pull requests to the your cloud provider as part of your CI pipeline.
* [Shutit](https://github.com/ianmiell/shutit) ⭐ 2,142 | 🐛 9 | 🌐 Python | 📅 2022-08-14 :ice\_cube: - Tool for building and maintaining complex Docker deployments.
* [udocker](https://github.com/indigo-dc/udocker) ⭐ 1,733 | 🐛 38 | 🌐 Python | 📅 2025-08-13 - A tool to execute simple docker containers in batch or interactive systems without root privileges.
* [subuser](https://github.com/subuser-security/subuser) ⭐ 894 | 🐛 43 | 🌐 Python | 📅 2025-02-23 - Makes it easy to securely and portably run graphical desktop applications in Docker.
* [Dray](https://github.com/CenturyLinkLabs/dray) ⭐ 385 | 🐛 7 | 🌐 Go | 📅 2020-01-24 :ice\_cube: - An engine for managing the execution of container-based workflows.
* [dexec](https://github.com/docker-exec/dexec) ⭐ 332 | 🐛 17 | 🌐 Go | 📅 2021-05-13 :ice\_cube: - Command line interface written in Go for running code with Docker Exec images.
* [Terraform cloud-init config](https://github.com/christippett/terraform-cloudinit-container-server) ⭐ 119 | 🐛 4 | 🌐 HCL | 📅 2022-08-19 :ice\_cube: - Terraform module for deploying a single Docker image or `docker-compose.yaml` file to any Cloud™ VM.
* [Vagrant - Docker provider](https://developer.hashicorp.com/vagrant/docs/providers/docker/basics) - Good starting point is [vagrant-docker-example](https://github.com/bubenkoff/vagrant-docker-example) ⭐ 113 | 🐛 2 | 📅 2015-10-23.
* [Hokusai](https://github.com/artsy/hokusai) ⭐ 98 | 🐛 21 | 🌐 Python | 📅 2026-03-23 - A Docker + Kubernetes CLI for application developers; used to containerize an application and to manage its lifecycle throughout development, testing, and release cycles. From [artsy](https://github.com/artsy).
* [dockerized](https://github.com/benzaita/dockerized-cli) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2024-02-27 :ice\_cube: - Seamlessly execute commands in a container.
* [Turbo](https://github.com/ramitsurana/turbo) ⭐ 27 | 🐛 1 | 🌐 Go | 📅 2021-12-22 :ice\_cube: - Simple and Powerful utility for docker. By [ramitsurana][ramitsurana].
* [Ansible](https://docs.ansible.com/projects/ansible/latest/collections/community/general/docker_container_module.html) - Manage the life cycle of Docker containers. By RedHat.

## Services based on Docker (mostly :yen:)

### CI Services

* [CircleCI](https://circleci.com/) - :yen: Push or pull Docker images from your build environment, or build and run containers right on CircleCI.
* [CodeFresh](https://codefresh.io) - :yen: Everything you need to build, test, and share your Docker applications. Provides automated end to end testing.
* [CodeShip](https://www.cloudbees.com/blog/how-to-run-codeship-parallel-test-pipelines-efficiently-for-optimal-ci-parallelization) - :yen: Work with your established Docker workflows while automating your testing and deployment tasks with our hosted platform dedicated to speed and security.
* [ConcourseCI](https://concourse-ci.org) - :yen: A CI SaaS platform for developers and DevOps teams pipeline oriented.
* [Semaphore CI](https://semaphore.io/) :yen: — A high-performance cloud solution that makes it easy to build, test and ship your containers to production.
* [TravisCI](https://www.travis-ci.com/) - :yen: A Free github projects continuous integration Saas platform for developers and Devops.

### CaaS

* [Amazon ECS](https://aws.amazon.com/ecs/) - :yen: A management service on EC2 that supports Docker containers.
* [Appfleet](https://appfleet.com/) - :yen: Edge platform to deploy and manage containerized services globally. The system will route the traffic to the closest location for lower latency.
* [Azure AKS](https://azure.microsoft.com/en-us/products/kubernetes-service/) - :yen: Simplify Kubernetes management, deployment, and operations. Use a fully managed Kubernetes container orchestration service.
* [Cloud 66](https://www.cloud66.com) - :yen: Full-stack hosted container management as a service.
* [Giant Swarm](https://www.giantswarm.io/) - :yen: Simple microservice infrastructure. Deploy your containers in seconds.
* [Google Container Engine](https://docs.cloud.google.com/kubernetes-engine/docs) - :yen: Docker containers on Google Cloud Computing powered by [Kubernetes][kubernetes].
* [Mesosphere DC/OS Platform](https://d2iq.com/products/dcos) - :yen: Integrated platform for data and containers built on Apache Mesos.
* [Red Hat OpenShift Dedicated](https://www.redhat.com/en/technologies/cloud-computing/openshift/dedicated) - :yen: Fully-managed Red Hat® OpenShift® service on Amazon Web Services and Google Cloud.
* [Triton](https://www.joyent.com/) - :yen: Elastic container-native infrastructure by Joyent.

### Monitoring Services

* [SPM for Docker](https://github.com/sematext/sematext-agent-docker) ⭐ 208 | 🐛 1 | 🌐 JavaScript | 📅 2023-12-09 :ice\_cube: - :yen: Monitoring of host and container metrics, Docker events and logs. Automatic log parser. Anomaly Detection and alerting for metrics and logs. [sematext](https://github.com/sematext).
* [AppDynamics](https://github.com/Appdynamics/docker-monitoring-extension) ⭐ 5 | 🐛 3 | 🌐 Java | 📅 2024-10-02 - Docker Monitoring extension gathers metrics from the Docker Remote API, either using Unix Socket or TCP.
* [Better Stack](https://betterstack.com/community/guides/scaling-docker/) - :yen: A Docker-compatible observability stack that delivers robust log aggregation and uptime monitoring capabilities for various software application.
* [Broadcom Docker Monitoring](https://www.broadcom.com/info/aiops/docker-monitoring) - :yen: Agile Operations solutions from Broadcom deliver the modern Docker monitoring businesses need to accelerate and optimize the performance of microservices and the dynamic Docker environments running them. Monitor both the Docker environment and apps that run inside them. (former CA Technologies).
* [Collecting docker logs and stats with Splunk](https://www.splunk.com/en_us/blog/tips-and-tricks/collecting-docker-logs-and-stats-with-splunk.html)
* [Datadog](https://www.datadoghq.com/) - :yen: Datadog is a full-stack monitoring service for large-scale cloud environments that aggregates metrics/events from servers, databases, and applications. It includes support for Docker, Kubernetes, and Mesos.
* [Prometheus](https://prometheus.io/) - :yen: Open-source service monitoring system and time series database.
* [Site24x7](https://www.site24x7.com/docker-monitoring.html) - :yen: Docker Monitoring for DevOps and IT is a SaaS Pay per Host model.
* [Sysdig Monitor](https://www.sysdig.com/products/monitor) - :yen: Sysdig Monitor can be used as either software or a SaaS service to monitor, alert, and troubleshoot containers using system calls. It has container-specific features for Docker and Kubernetes.

# Useful Resources

* **[Valuable Docker Links](http://nane.kratzke.pages.mylab.th-luebeck.de/about/blog/2014/08/24/valuable-docker-links/)** High quality articles about docker! **MUST SEE**

* [Cloud Native Landscape](https://github.com/cncf/landscape) ⭐ 9,874 | 🐛 45 | 📅 2026-04-23

* [Docker Blog](https://www.docker.com/blog/) - Regular updates about Docker, the community and tools.

* [Docker Certification](https://intellipaat.com/docker-training-course/?US) :yen: will help you to will Learn Docker containerization, running Docker containers, Image creation, Dockerfile, Docker orchestration, security best practices, and more through hands-on projects and case studies and helps to clear Docker Certified Associate.

* [Docker dev bookmarks](https://www.codever.dev/search?q=docker) - Use the tag [docker](https://www.codever.dev/bookmarks/t/docker).

* [Docker in Action, Second Edition](https://www.manning.com/books/docker-in-action-second-edition)

* [Docker in Practice, Second Edition](https://www.manning.com/books/docker-in-practice-second-edition)

* [Docker packaging guide for Python](https://pythonspeed.com/docker/) - A series of detailed articles on the specifics of Docker packaging for Python.

* [Learn Docker in a Month of Lunches](https://www.manning.com/books/learn-docker-in-a-month-of-lunches)

* [Learn Docker](https://coursesity.com/blog/best-docker-tutorials/) - Learn Docker - curated list of the top online docker tutorials and courses.

* [Programming Community Curated Resources for learning Docker](https://hackr.io/tutorials/learn-docker)

## Awesome Lists

* [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) ⭐ 288,217 | 🐛 0 | 📅 2026-04-18 list of Free Software network services and web applications which can be hosted locally by running in a classical way (setup local web server and run applications from there) or in a Docker container. By [Kickball](https://github.com/Kickball)
* [Awesome Compose](https://github.com/docker/awesome-compose) ⭐ 44,989 | 🐛 363 | 🌐 HTML | 📅 2026-04-22 - Docker Compose samples.
* [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) ⭐ 33,683 | 🐛 61 | 📅 2026-04-23 by [n1trux](https://github.com/n1trux)
* [ToolsOfTheTrade](https://github.com/cjbarber/ToolsOfTheTrade) ⭐ 17,019 | 🐛 9 | 📅 2026-03-13 a list of SaaS and On premise applications by [cjbarber](https://github.com/cjbarber)
* [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes) ⭐ 15,903 | 🐛 59 | 🌐 Shell | 📅 2026-02-27 by [ramitsurana][ramitsurana]
* [Awesome Linux Container](https://github.com/Friz-zy/awesome-linux-containers) ⭐ 2,047 | 🐛 10 | 📅 2024-04-09 more general about container than this repo, by [Friz-zy](https://github.com/Friz-zy).
* [Awesome CI/CD](https://github.com/cicdops/awesome-ciandcd) ⭐ 1,993 | 🐛 25 | 📅 2026-04-14 :ice\_cube: - Not specific to docker but relevant.

## Demos and Examples

* [Local Docker DB](https://github.com/alexmacarthur/local-docker-db) ⭐ 298 | 🐛 3 | 🌐 Go | 📅 2024-05-04 a list of docker-compose samples for a lot of databases by [alexmacarthur](https://github.com/alexmacarthur)
* [Webstack-micro](https://github.com/ferbs/webstack-micro) ⚠️ Archived Demo web app showing how Docker Compose might be used to set up an API Gateway, centralized authentication, background workers, and WebSockets as containerized services.
* [An Annotated Docker Config for Frontend Web Development](https://nystudio107.com/blog/an-annotated-docker-config-for-frontend-web-development) A local development environment with Docker allows you to shrink-wrap the devops your project needs as config, making onboarding frictionless.

## Good Tips

* [Docker Caveats](http://docker-saigon.github.io/post/Docker-Caveats/) What You Should Know About Running Docker In Production (written 11 APRIL 2016) **MUST SEE**
* [Docker Containers on the Desktop](https://blog.jessfraz.com/post/docker-containers-on-the-desktop/) - The **funniest way** to learn about docker by [jessfraz][jessfraz] who also gave a [presentation](https://www.youtube.com/watch?v=1qlLUf7KtAw) about it @ DockerCon 2015.
* [Docker vs. VMs? Combining Both for Cloud Portability Nirvana](https://www.flexera.com/blog/finops/)
* [Dockerfile best practices](https://github.com/hexops/dockerfile) ⭐ 4,091 | 🐛 3 | 🌐 Dockerfile | 📅 2021-08-08 :ice\_cube: - This repository has best-practices for writing Dockerfiles.
* [Don't Repeat Yourself with Anchors, Aliases and Extensions in Docker Compose Files](https://medium.com/@kinghuang/docker-compose-anchors-aliases-extensions-a1e4105d70bd) by [King Chung Huang](https://github.com/kinghuang)
* [GUI Apps with Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/) by [fgrehm][fgrehm]

## Raspberry Pi & ARM

* [Get Docker up and running on the RaspberryPi in three steps](https://github.com/umiddelb/armhf/wiki/Get-Docker-up-and-running-on-the-RaspberryPi-%28ARMv6%29-in-three-steps) ⭐ 733 | 🐛 0 | 🌐 Shell | 📅 2016-01-28
* [Installing, running, using Docker on armhf (ARMv7) devices](https://github.com/umiddelb/armhf/wiki/Installing,-running,-using-docker-on-armhf-%28ARMv7%29-devices) ⭐ 733 | 🐛 0 | 🌐 Shell | 📅 2016-01-28
* [Docker Pirates ARMed with explosive stuff](https://blog.hypriot.com/) Huge resource on clustering, swarm, docker, pre-installed image for SD card on Raspberry Pi
* [git push docker containers to linux devices](https://www.balena.io) Modern DevOps for IoT, leveraging git and Docker.

## Security

* [How CVE's are handled on Offical Docker Images](https://github.com/docker-library/official-images/issues/1448) ⭐ 6,946 | 🐛 45 | 🌐 Shell | 📅 2026-04-24
* [Docker Secure Deployment Guidelines](https://github.com/AonCyberLabs/Docker-Secure-Deployment-Guidelines) ⭐ 605 | 🐛 1 | 📅 2016-11-01
* [CVE Scanning Alpine images with Multi-stage builds in Docker 17.05](https://github.com/tomwillfixit/alpine-cvecheck) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2017-05-07 by [tomwillfixit](https://twitter.com/tomwillfixit)
* [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
* [Docker Security - Quick Reference](https://binarymist.io/publication/docker-security/)
* [Docker Security: Are Your Containers Tightly Secured to the Ship? SlideShare](https://www.slideshare.net/slideshow/docker-security-are-your-containers-tightly-secured-to-the-ship/43834790)
* [Lynis is an open source security auditing tool including Docker auditing](https://cisofy.com/lynis/)
* [Security Best Practices for Building Docker Images](https://linux-audit.com/tags/docker/)
* [Software Engineering Radio interview of Docker Security Team Lead (Diogo Mónica)](https://www.se-radio.net/2017/05/se-radio-episode-290-diogo-monica-on-docker-security/)
* [Ten Docker Image Security Best Practices Cheat Sheet](https://snyk.io/blog/10-docker-image-security-best-practices/)
* [Top ten most popular docker images each contain at least 30 vulnerabilities](https://snyk.io/blog/top-ten-most-popular-docker-images-each-contain-at-least-30-vulnerabilities/)
* [Tuning Docker with the newest security enhancements](https://opensource.com/business/15/3/docker-security-tuning)
* [10 best practices to containerize Node.js web applications with Docker](https://snyk.io/blog/10-best-practices-to-containerize-nodejs-web-applications-with-docker/)

## Videos

* [Contributing to Docker by Andrew "Tianon" Page (InfoSiftr)](https://www.youtube.com/watch?v=1jwo8-1HYYg) (34:31)
* [Deploying and scaling applications with Docker, Swarm, and a tiny bit of Python magic](https://www.youtube.com/watch?v=GpHMTR7P2Ms) (3:11:06) by [jpetazzo][jpetazzo]
* [Docker and SELinux by Daniel Walsh from Red Hat](https://www.youtube.com/watch?v=zWGFqMuEHdw) (40:23)
* [Docker Course](https://www.youtube.com/watch?v=UZpyvK6UGFo) (Spanish) by [pablokbs](https://github.com/pablokbs)
* [Docker for Developers](https://www.youtube.com/watch?v=FdkNAjjO5yQ) (54:26) by [jpetazzo][jpetazzo] <== Good introduction, context, demo
* [Docker from scratch](https://www.youtube.com/playlist?list=PLLhEJK7fQIxD-btrjrqdEfQHbkZnQrmqE) (1:22:01) on YouTube by Paris Nakita Kejser
* [Docker: How to Use Your Own Private Registry](https://www.youtube.com/watch?v=CAewZCBT4PI) (15:01)
* [Docker in Production](https://www.youtube.com/watch?v=Glk5d5WP6MI) by [jpetazzo][jpetazzo] (36:05)
* [Docker Primer to Docker Compose](https://www.youtube.com/watch?v=G-s2GXGAjTk) (1:56:45) on YouTube by LoginRadius
* [Docker Registry from scratch](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAz3d4Fj3edq7UcxEhdTCBm) (44:40) on YouTube by Paris Nakita Kejser
* [Docker Swarm from scratch](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAY4gZd1Wl-GsLvg-e9Ap1e) (1:41:28) on YouTube by Paris Nakita Kejser
* [Extending Docker with Plugins](https://vimeo.com/110835013) (15:21)
* [From Local Docker Development to Production Deployments](https://www.youtube.com/watch?v=7CZFpHUPqXw) by [jpetazzo][jpetazzo] @ AWS re:Invent 2015
* [Immutable Infrastructure with Docker and EC2 by Michael Bryzek (Gilt)](https://www.youtube.com/watch?v=GaHzdqFithc) (42:04)
* [Introduction to Docker and containers](https://www.youtube.com/watch?v=ZVaRK10HBjo) (3:09:00) by [jpetazzo][jpetazzo]
* [Logging on Docker: What You Need to Know](https://vimeo.com/123341629) (51:27)
* [Performance Analysis of Docker - Jeremy Eder](https://www.youtube.com/watch?v=6f2E6PKYb0w) (1:36:58)
* [Scalable Microservices with Kubernetes](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615) Free Udacity course
* [State of containers: a debate with CoreOS, VMware and Google](https://www.youtube.com/watch?v=IiITP3yIRd8) (27:38)

# Communities and Meetups

## Brazilian

* [Docker BR on Telegram](https://telegram.me/dockerbr)

## English

* [Docker Community](https://www.docker.com/community/)
* [Docker Events](https://www.docker.com/events/)
* [Docker Online Meetup](https://www.meetup.com/en-AU/Docker-Online-Meetup/)
* [Docker Reddit Community](https://www.reddit.com/r/docker/)

## Russian

* [Docker Russian-speaking Community](https://t.me/docker_ru)

## Spanish

* [Docker Tips](https://dockertips.com/)

## Stargazers over time

[![Stargazers over time](https://starchart.cc/veggiemonk/awesome-docker.svg?variant=adaptive)](https://starchart.cc/veggiemonk/awesome-docker)

[contributing]: https://github.com/veggiemonk/awesome-docker/blob/master/.github/CONTRIBUTING.md

[calico]: https://github.com/projectcalico/calico

[containx]: https://github.com/ContainX

[coreos]: https://github.com/coreos

[deepfence]: https://github.com/deepfence

[distribution]: https://github.com/docker/distribution

[docker-flow]: https://github.com/docker-flow

[docker-for-windows]: https://docs.docker.com/desktop/setup/install/windows-install/

[docker]: https://github.com/docker

[dozzle]: https://github.com/amir20/dozzle

[editreadme]: https://github.com/veggiemonk/awesome-docker/edit/master/README.md

[fgrehm]: https://github.com/fgrehm

[gliderlabs]: https://github.com/gliderlabs

[googlecontainertools]: https://github.com/GoogleContainerTools

[inspec]: https://github.com/inspec/inspec

[jessfraz]: https://github.com/jessfraz

[jpetazzo]: https://github.com/jpetazzo

[jwilder]: https://github.com/jwilder

[kubernetes]: https://kubernetes.io

[lispyclouds]: https://github.com/lispyclouds

[nginxproxy]: https://github.com/nginx-proxy/nginx-proxy

[openshift]: https://okd.io/

[powerman]: https://github.com/powerman

[progrium]: https://github.com/progrium

[ramitsurana]: https://github.com/ramitsurana

[sindresorhus]: https://github.com/sindresorhus/awesome

[spotify]: https://github.com/spotify

[vegasbrianc]: https://github.com/vegasbrianc

[vmware]: https://github.com/vmware

[byrnedo]: https://github.com/byrnedo

[crazy-max]: https://github.com/crazy-max

[skanehira]: https://github.com/skanehira

[akito]: https://github.com/theAkito

[peco602]: https://github.com/Peco602

[weave]: https://github.com/weaveworks/weave
