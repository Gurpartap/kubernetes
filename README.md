# Kubernetes

[![GoDoc](https://godoc.org/github.com/GoogleCloudPlatform/kubernetes?status.png)](https://godoc.org/github.com/GoogleCloudPlatform/kubernetes)
[![Travis](https://travis-ci.org/GoogleCloudPlatform/kubernetes.svg?branch=master)](https://travis-ci.org/GoogleCloudPlatform/kubernetes)

> Kubernetes is an open source implementation of container cluster management.

Package your application up with Docker, then let Kubernetes manage and run it for you.

[Watch Kubernetes @ Google I/O 2014](http://youtu.be/tsk0pWf4ipw)

[![Watch Kubernetes @ Google I/O 2014](http://i.imgur.com/DbgdxGx.png)](http://youtu.be/tsk0pWf4ipw)

#### Kubernetes is community driven!

Kubernetes is a community driven cluster manager that goes wherever your Linux application container can go, from your laptop to the cloud and anywhere in between. It was created by Google drawing on over ten years of experience running containers at massive scale, but is owned and powered by a diverse set of contributors.

#### It can run anywhere!

Even though the initial development was done on Google Compute Engine (which is why so our instructions and scripts are built around that), Kubernetes can run on any cluster infrastructure. If you make it work on infrastructure that is not documented, please let us know and contribute instructions/code.

#### ... and it is in pre-production beta!

While the concepts and architecture in Kubernetes represent years of experience designing and building large scale cluster manager at Google, the Kubernetes project is still under heavy development. Expect bugs, design and API changes as we bring it to a stable, production product over the coming year.

## Getting Started

The getting started document, found in the following links, outlines how to obtain packages and installation specifics for your platform. The examples help individuals to get started quickly and gain a foundational knowledge of Kubernetes.

##### First steps

* [Creating a Kubernetes cluster]()
* [Deploy a simple multi-tiered guestbook app]()
* [Deploy an app that demonstrates zero-downtime deployment](https://github.com/GoogleCloudPlatform/kubernetes/blob/master/examples/update-demo/README.md)

##### Where to go next?

The following getting started tutorials are also available:

* [`kubecfg` command line tool](https://github.com/GoogleCloudPlatform/kubernetes/blob/master/docs/cli.md)
* [Kubernetes API Documentation](http://cdn.rawgit.com/GoogleCloudPlatform/kubernetes/31a0daae3627c91bc96e1f02a6344cd76e294791/api/kubernetes.html)
* [Kubernetes Client Libraries](https://github.com/GoogleCloudPlatform/kubernetes/blob/master/docs/client-libraries.md)

* [Cluster monitoring with Heapster and cAdvisor](https://github.com/GoogleCloudPlatform/heapster)

##### A list of all the tutorials and community projects can be found here:
* [Kubernetes tutorials and community projects]()

## Releases

Kubernetes releases are available for download via the following link:

* [http://kubernetes.io/releases](http://kubernetes.io/releases)

## Kubernetes in depth

Kubernetes is written in Go. It is highly modular and designed from the start to be adaptable and extensible.

Interested in taking a peak inside Kubernetes? You should start by reading the design overview which introduces core Kubernetes concepts and components. After that, you probably want to take a look at the API documentation and learn about the kubecfg command line tool.

- Pods
- Labels
- Services
- Replication Controllers
- Master components (API Server, Controller Manager and Scheduler)
- Minion components (Kubelet and Proxy)

## FAQ

See [here]() for a list of Frequently Asked Questions

## More information about the project
* Release notes
* [Kubernetes Design](https://github.com/GoogleCloudPlatform/kubernetes/blob/master/DESIGN.md)
* [Cluster Security](https://github.com/GoogleCloudPlatform/kubernetes/blob/master/DESIGN.md#cluster-security)
* [Testing out flaky tests](https://github.com/GoogleCloudPlatform/kubernetes/blob/master/docs/flaky-tests.md)

