# Openshift 4 AWS Deployment Steps

The promise of Openshift 4 is that it can be deployed in any cloud may it be in a public or private or hybrid cloud. Here, I'll demonstrate how easy it is to first try it out on the public cloud such as AWS.

### Prequisites
![RedHat Landing Page](https://github.com/edmacabebe/openangles/blob/master/images/rh-landing.png "Red Hat Developer SSO")
1. Must have a [Red Hat Developer Account](https://cloud.redhat.com/). Login in and/or go directly to the [Cluster Manager](https://cloud.redhat.com/openshift/install)
![RedHat Landing Page](https://github.com/edmacabebe/openangles/blob/master/images/rh-multicloud-install-portal.png "Red Hat Developer SSO")
There are 2 approaches to deploy Openshift 4 to AWS, One is IPI or the Installer-Provisioned Infrastructure and Second, is the UPI or User-Provisioned Infrastructure. In this 1st part or installation approach, the focus is on the former, i.e., IPI - click it. 
![Install approaches](https://github.com/edmacabebe/openangles/blob/master/images/rh-ipi.png "Openshift AWS IPI")
We will then see the procedure steps as below
2. Must have a "paying" account in AWS
3. Must have acquired a Domain name 
4. Download the Openshift Installer
5. Download the Pull secret
5. Download the Command Line Tools
* oc
* kubectl
![AWS IPI Procedures](https://github.com/edmacabebe/openangles/blob/master/images/rh-aws-procedures.png "Openshift AWS IPI Procedures")




