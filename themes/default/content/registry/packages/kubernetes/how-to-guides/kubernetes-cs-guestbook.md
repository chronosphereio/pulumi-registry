---
title: "Simple and Component-based Kubernetes Guestbook Apps | C#"
h1: "Simple and Component-based Kubernetes Guestbook Apps"
linktitle: "Simple and Component-based Kubernetes Guestbook Apps"
meta_desc: "Simple and Component-based Kubernetes Guestbook Apps How-to Guide using C#"
no_edit_this_page: true
cloud: kubernetes
language: cs
layout: package
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/mktutorial. -->

<p class="mb-4 flex">
    <a class="flex flex-wrap items-center rounded-md font-display text-lg text-white bg-blue-600 border-2 border-blue-600 px-2 mr-2 whitespace-no-wrap hover:text-white" style="height: 45px;" href="https://github.com/pulumi/examples/tree/master/kubernetes-cs-guestbook" target="_blank">
        <span><i class="fab fa-github pr-2"></i> View Code</span>
    </a>
    <a href="https://app.pulumi.com/new?template=https://github.com/pulumi/examples/tree/master/kubernetes-cs-guestbook/components" target="_blank">
        <img src="https://get.pulumi.com/new/button.svg" alt="Deploy">
    </a>
</p>


A port of the standard [Kubernetes Guestbook](https://kubernetes.io/docs/tutorials/stateless-application/guestbook/)
to Pulumi. This example shows you how to build and deploy a simple, multi-tier web application using Kubernetes and
Docker, and consists of three components:

* A single-instance Redis master to store guestbook entries
* Multiple replicated Redis instances to serve reads
* Multiple web frontend instances

In this directory, you will find two variants of the Guestbook:

1. [simple/](https://github.com/pulumi/examples/blob/master/kubernetes-cs-guestbook/simple) is a straight port of the original YAML.
2. [components](https://github.com/pulumi/examples/blob/master/kubernetes-cs-guestbook/components) demonstrates benefits of using a real language, namely eliminating boilerplate through
   the use of real component abstractions.

Both examples provision the exact same Kubernetes Guestbook application, but showcase different aspects of Pulumi.
