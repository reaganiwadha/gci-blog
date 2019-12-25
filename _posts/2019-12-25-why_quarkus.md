---
layout: post
title:  "Fast and Cheap Java Stack? What!? Quarkus"
date:   2019-12-25 18:42:54 +0700
categories: jekyll update
---
# Supersonic Subatomic Java


Live reloading is great!             |
:-------------------------:|:-------------------------:
![Quarks](https://quarkus.io/assets/images/homepage_comic_1.png)  |  ![Quarks](https://quarkus.io/assets/images/homepage_comic_2.png) 

Have you ever thought that writing server backend using java is just plain boring and not fun? Me too. Until i discovered something called "Quarkus"

But what is Quarkus exactly? According to [Red Hat](https://developers.redhat.com/blog/2019/03/07/quarkus-next-generation-kubernetes-native-java-framework/) 

> Quarkus is a Kubernetes Native Java framework tailored for GraalVM and HotSpot, crafted from best-of-breed Java libraries and standards. The goal of Quarkus is to make Java a leading platform in Kubernetes and serverless environments while offering developers a unified reactive and imperative programming model to optimally address a wider range of distributed application architectures.

> Quarkus provides an effective solution for running Java in this new world of serverless, microservices, containers, Kubernetes, FaaS, and the cloud because it has been designed with these in mind.

This is great news for Java developers! That means that Java is back in the game in container platforms and serverless!
Personally, I find Java syntax beautiful than other languages. But sometimes writing backend for services using Java is just feels... enormous (eh? i dont know i can't come up with words)

## Use Case
You can actually deploy quarkus almost everywhere! Microservices, FaaS, Serverless applications... You name it! Personally i like to deploy quarkus as a backend API for some WebApps. Not only that, Quarkus is easy to deploy since it is aimed to be deployed in container orchestration platforms like Kubernetes

## Cheap and Fast
Quarkus is blazing-fast and is cheap on memory since it is using the technique of [compile-time boot](https://quarkus.io/vision/container-first)

![Blazing Fast](https://quarkus.io/assets/images/quarkus_metrics_graphic_bootmem_wide.png)

## Architecture
Quarkus Architecture is pretty straight-forward since it is puts the developer in the king position. For example, if we wanted to make a straightforward application that greets the use with "Hello". We could make a ```hello``` endpoint and if you wanted to implement dependency injection, you can make the endpoint uses a ```greeting``` bean.

![Straightforward Architecture](https://quarkus.io/guides/images/getting-started-architecture.png)


## Syntax
One thing to note is that Quarkus syntax is beautiful and have a great balance between Verbose and Simple (personally) In Quarkus, you can write [code in an imperative way or in a reactive way](https://developers.redhat.com/blog/2019/11/18/how-quarkus-brings-imperative-and-reactive-programming-together/).

### Imperative
{% gist 8b4efa4c9176d0c4f4dcebc464db0644 %}

### Reactive
{% gist 77519e971c2f7500747452ed5c235baa %}

## Benefits to using Quarkus as a developer

* ✅ Live reloading is blazing fast with Zero Config
* ✅ Native executable generation? What's that?
* ✅ Code is very streamlined and flexible
* ✅ Unified Configuration
* ✅ Easy Deployments

## Conclusion
Quarkus is a great way for Java Developers looking forward to deploy Microservices, FaaS or anything else! 