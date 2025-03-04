---
title: Object
id: object
date: 2020-10-12
full_link: /docs/concepts/overview/working-with-objects/#kubernetes-objects
short_description: >
   An entity in the Kubernetes system, representing part of the state of your cluster.
aka:
tags:
- architecture
- fundamental
---
An entity in the Kubernetes system. An object is an
{{< glossary_tooltip text="API resource" term_id="api-resource" >}} that the Kubernetes API
uses to represent the state of your cluster.
<!--more-->
A Kubernetes object is typically a “record of intent”—once you create the object, the Kubernetes
{{< glossary_tooltip text="control plane" term_id="control-plane" >}} works constantly to ensure
that the item it represents actually exists.
By creating an object, you're effectively telling the Kubernetes system what you want that part of
your cluster's workload to look like; this is your cluster's desired state.
