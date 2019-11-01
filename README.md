# Deploying Java Microservices to OpenShift on IBM Cloud

This workshop demonstrates how to build a microservice with Java and how to deploy it to OpenShift on the IBM Cloud. It is an adaption of the workshop provided by [IBM Developer UK](https://github.com/nheidloff/openshift-on-ibm-cloud-workshops/tree/master/2-deploying-to-openshift#deploying-java-microservices-to-openshift-on-ibm-cloud)

The microservice is kept as simple as possible, so that it can be used as a starting point for other microservices. The microservice has been developed with Java EE and [Eclipse MicroProfile](https://microprofile.io/).

There are [various ways to deploy applications to OpenShift](http://heidloff.net/article/deploying-open-liberty-microservices-openshift/). The options have different advantages and disadvantages which are explained in the following labs.

## What to Expect

The content is organized into 4 parts. In the first, we'll get our microservice running locally. In the second part, we'll look at our Java implementation in more depth. The third part will be us deploying the application we created locally to an OpenShift cluster in the IBM Cloud. In the final part, we'll look at other methods of using OpenShift to deploy our application.

Before we get into that, we have a couple prerequisites. You'll need to set up your development environment. We've got steps for you to do that in [this link](https://github.com/pnbrown/openshift-on-ibm-cloud-workshops/blob/master/2-deploying-to-openshift/documentation/1-prereqs.md). The final prerequisite is creating an IBM Cloud account which you can do through [this link](https://ibm.biz/BdzQDd)
