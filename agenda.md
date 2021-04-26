# Docker workshop agenda

0. Introduction

1. Motivation
   - different languages
   - unification of runtime: dev laptop / server cloud
   - lightweight: no OS, process, network, user namespace
   - compare to VMs, LXC

2. Terminology
   - image (hash / tag / repository)
   - container
   - Docker daemon
   - Docker client

--- coffee break to 9:05 ---

3. Docker HUB
   - pull hello-world:latest
   - run
   - run options: --rm, -ti
   - node:latest, ruby:latest, python:latest

4. Simple app
   - simple Python app
   - concept of layers
   - Dockerfile

--- coffee break to 10:55 ---

5. More advanced app
   - Flask Python app
   - more Dockerfile syntax
   - Docker build caching + Dockerfile command ordering
   - ports
   - volumes
   - env vars
   - entrypoint
   - detached + ps + logs + exec

6. Docker compose
   - syntax
   - networking (add mysql service)

7. Container orchestration
   - stateful / stateless app
   - Kubernetes

8. Q/A
