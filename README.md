# Deploying Java Microservices to OpenShift on IBM Cloud

This workshop demonstrates how to build a microservice with Java and how to deploy it to OpenShift on the IBM Cloud. It is an adaption of the workshop provided by [IBM Developer UK](https://github.com/nheidloff/openshift-on-ibm-cloud-workshops/tree/master/2-deploying-to-openshift#deploying-java-microservices-to-openshift-on-ibm-cloud).

The microservice is kept as simple as possible, so that it can be used as a starting point for other microservices. The microservice has been developed with Java EE and [Eclipse MicroProfile](https://microprofile.io/).

There are [various ways to deploy applications to OpenShift](http://heidloff.net/article/deploying-open-liberty-microservices-openshift/). The options have different advantages and disadvantages which are explained in the following labs.

This README is a derivative of the second part of a two part workshop about OpenShift on IBM Cloud. The full workshop is available from [IBM Developer UK](https://github.com/IBMDeveloperUK/openshift-on-ibm-cloud-workshops).

## What to Expect

The content is organized into 4 parts. In the first, we'll get our microservice running locally. In the second part, we'll look at our Java implementation in more depth. The third part will be us deploying the application we created locally to an OpenShift cluster in the IBM Cloud. In the final part, we'll look at other methods of using OpenShift to deploy our application.

Before we get into that, we have a couple prerequisites. You'll need to set up your development environment. We've got steps for you to do that in [here](https://github.com/pnbrown/openshift-on-ibm-cloud-workshops/blob/master/2-deploying-to-openshift/documentation/1-prereqs.md). The final prerequisite is creating an IBM Cloud account which you can do through [a special link for this event](https://ibm.biz/BdzQDd).

## Part 1: Running the Microservice Locally

In this section we'll quickly get you to a proof-of-concept that runs locally upon which we'll build for the rest of the workshop. You'll also be able to build from this for your own future services. This section will also outline the capabilities included in this template microservice.

The step-by-step instructions are contained in [Lab 2](https://github.com/nheidloff/openshift-on-ibm-cloud-workshops/blob/master/2-deploying-to-openshift/documentation/2-docker.md) of the full workshop.

## Part 2: Understanding the Java Implementation

In Part 1 we quickly covered what was necessary to get your local instance running. In this section we look a little bit more in depth at our Java implementation so you have all that you need to build upon this in your own projects. 

The step-by-step instructions are contained in [Lab 3](https://github.com/nheidloff/openshift-on-ibm-cloud-workshops/blob/master/2-deploying-to-openshift/documentation/3-java.md#lab-3---understanding-the-java-implementation) of the full workshop.

## Part 3: Deploying to OpenShift

Now that our services can run locally and we understand their construction, we go over one technology for deploying our microservice for others to use: OpenShift.

First we need to get you all your own OpenShift Clusters. We'll take some time to cover that now.

Once folks have gotten their clusters, the next sep will be starting the deployment of our containers that we've just made to OpenShift. The full instructions for that portion are contained in [Lab 4](https://github.com/nheidloff/openshift-on-ibm-cloud-workshops/blob/master/2-deploying-to-openshift/documentation/4-openshift.md#lab-4---deploying-to-openshift) of the full workshop.

## Part 4: Other Deployment Methods for OpenShift

Congratulations on getting your microservice deployed! The steps that we took are just one of the ways in which we can deploy our microservices to OpenShift. Follow along to see three more methods for deployment. They are listed below:

1. Deploy from existing containers on Docker Hub
2. Deploy using GitHub Repositories with Dockerfiles defined
3. Deploy using the Source to Image functionality in OpenShift

## Wrap Up

Thank you so much for following along with us. We hope you were able to learn and you found the information helpful. Please do  reach out if you have any questions. We'll see you soon!

P.S. If you'd like to see a full application built in a method similar to what we've outlined above, check out the [Example Health App from IBM](https://github.com/IBM/example-health-jee-openshift) and the accompanying [code pattern series on IBM Developer](https://developer.ibm.com/series/systems-example-health-series/).
