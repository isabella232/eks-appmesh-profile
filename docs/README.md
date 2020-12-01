---
title: EKS GitOps hands-on
meta:
  - name: keywords
    content: gitops kubernetes aws eks eksctl appmesh fluxcd flagger
home: true
sidebar: auto
#heroImage: /gitops-appmesh.png
heroText: Welcome to the EKS GitOps challenge
tagline: Get hands-on experience with GitOps and Canary Deployments (“Progressive Delivery”)
actionText: Get Started →
actionLink: /prerequisites/
#features:
#- title: Flux CD
#  details: Flux is a tool for keeping Kubernetes clusters in sync with sources of configuration (like Git and Helm repositories), and automating updates to configuration when there is new code to deploy.
#- title: App Mesh
#  details: AWS App Mesh is a service mesh that provides application-level networking to make it easy for your services to
#    communicate with each other across multiple types of compute infrastructure.
#- title: Flagger
#  details: Flagger is a Kubernetes operator that automates the promotion of canary deployments using 
#    App Mesh routing for traffic shifting, Prometheus metrics for canary analysis and Helm for testing.
footer: Apache License 2.0 | Copyright © 2020 Weaveworks
---

This is a self-paced online workshop where you will get hands-on experience with
GitOps and Progressive Delivery using Amazon EKS, eksctl, AWS App Mesh, Flux and Flagger. 

### Challenge

* Your own laptop and an internet connection
* Fill out this form [http://bit.ly/gitops-handson-form](http://bit.ly/gitops-handson-form)
* You own an AWS account (this costs about $1-2 to complete and about $7/week if you keep the cluster)
* Follow the self-paced workshop instructions (you can stop right before the canary rollback step)
* You have completed the hands-on when you enter:
`$ kubectl -n demo get canary`
and get the result:
`podinfo  Succeeded`

If we can come to your city, we will bring you this T-shirt. (So don't forget to fill out the form!)

<img src="https://eks.handson.flagger.dev/gitops-t-shirt.png" alt="prize" class="center">

### Getting help

* Invite yourself to the [Weave community slack](https://slack.weave.works/)
* Join the [#gitops-handson](https://weave-community.slack.com/messages/gitops-handson/) channel
