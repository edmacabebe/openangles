# Openshift 4 AWS Deployment Steps

The promise of Openshift 4 is that it can be deployed in any cloud may it be in a public or private or hybrid cloud. Here, I'll demonstrate how easy it is to first try it out on the public cloud such as AWS.

### Prequisites
![RedHat Landing Page](https://github.com/edmacabebe/openangles/blob/master/images/rh-landing.png "Red Hat Developer SSO")
1. Must have a [Red Hat Developer Account](https://cloud.redhat.com/). Login in and/or go directly to the [Cluster Manager](https://cloud.redhat.com/openshift/install)
![RedHat Landing Page](https://github.com/edmacabebe/openangles/blob/master/images/rh-multicloud-install-portal.png "Red Hat Developer SSO")
There are 2 approaches to deploy Openshift 4 to AWS, One is IPI or the Installer-Provisioned Infrastructure and Second, is the UPI or User-Provisioned Infrastructure. In this 1st part or installation approach, the focus is on the former, i.e., IPI - click it. 
![Install approaches](https://github.com/edmacabebe/openangles/blob/master/images/rh-ipi.png "Openshift AWS IPI")
We will then see the procedure steps as below
![AWS IPI Procedures](https://github.com/edmacabebe/openangles/blob/master/images/rh-aws-procedures.png "Openshift AWS IPI Procedures")
2. Must have a "paying" account in AWS
    - Create a publicly hosted zone to establish Start of Authority (SOA) and name server (NS) in route 53
    ![AWS Hosted Zone](https://github.com/edmacabebe/openangles/blob/master/images/aws-hostedzone.png "hosted zone")    
3. Must have acquired a Domain name. Either you have the budget or is serious enough to buy a serious sounding domain such as my mybiz.com or mybiz.com.ph. Or you don't, have the budget, or is not ready yet to spend $20 to $50 per year for a domain. A Libre option is, go [freenom.com](https://www.freenom.com) In such an approach, we can expect that our domain name can not be completly in accordance to our pre-determined signature name. If you decide to proceed, Login to it and create one. In my case, as below, I will use the "mcbee.ml" domain name that I've already created intended for this demo.
![My freenom domains dashboard](https://github.com/edmacabebe/openangles/blob/master/images/freenom.png "freenom.com dashboard") 
4. Download the Openshift Installer
    - Download the Openshift Installer Binary from the RH OCP4 official installer site. Be mindful of version, 4.1 and 4.2 supports AWS deployments and what your deployment machine is whether linux, windows or mac. So for mac, open the terminal
    - Create a OCP4 folder and get inside by calling
        ` mkdir OCP4 && cd OCP4`
    - Download the openshift installer:
        ```
            curl https://mirror.openshift.com/pub/openshift-v4/clients/ocp/latest/openshift-install-mac-4.1.4.tar.gz -o openshift-install-mac-4.1.4.tar.gz
            tar xvf openshift-install-mac-4.1.4.tar.gz
        ```     

5. Download the Pull secret
6. Download the Command Line Tools
* oc
* kubectl





