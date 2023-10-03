---
layout: post
title:  "Review of #10 k8s meetup | Cloud Native Lisbon x DevOps Lisbon"
date:   2023-10-03 18:02:00 +0100
categories: review meetup testing
---

Free pizza and free beers? 2 thumbs up!👍👍

Cloud Native Lisbon is a community group that organizes events every couple of months about containerization, microservices, CI/CD and DevOps stuff. Interestingly, it was founded by one of my colleagues at Ikigai Digital, João Aguiar. I didn't know that when I went.

Even though I don't use Kubernetes at my current role, I work with serverless architecture, I decided to go and didn't regret it.


The first talk was given by Urbano Freitas and it was called "Metrics-Based Deployments". From my understanding, it was about using Non-Functional Requirements Tests (NFR Tests) in the CI/CD pipelines to decide if a deploy is promoted from the Development environment to the next environment and so on until it gets to the Production environment. I think it's a good way to make sure the app remains performant and keep the users happy when adding new features.

It's not something that is specific to Kubernetes, it applies to serverless architectures too. Seems like a logical addition to the CI/CD pipelines after implementing the Testing Pyramid of Unit Tests, Integration Tests and End-to-end Tests.


The second talk was given by André Passos, and it was called "Pushing limits using the Cloud". It was about a big monolith that had its CI/CD in their own data center, where they provisioned thousands of Virtual Machines, and the migration of that CI/CD to a serverless architecture in the Google Cloud Platform. The need to do this change was because developers were stuck in a queue for their CI/CD jobs to run and they considered that the waiting time was wasting money.

Trying to take conclusions relevant to my serverless work was difficult at first, but after talking about it with other people there, I came away with one: make a decision not because it's trendy but because it brings actual value to the company.


Overall it was totally worth it, especially getting to talk with people there, and I'm looking forward to go again.
