# MLOps Foundation Engagement

## Red Hat AI/ML Service Offerings

In 2021, Red Hat released Red Hat OpenShift Data Science (RHODS) as a Tech Preview (TP) product, available as a managed service offering available on select cloud platforms.  Earlier this year Red Hat officially made RHODS Generally Available (GA), which included releasing support for Red Hat OpenShift Data Science as a self-managed service offering, bringing the data science tools to even more OpenShift users.

With the growing number of Red Hat customers seeking to expand their data science capabilities, the Data Science & Edge Practice at Red Hat has created several consulting service offerings to help meet our customers wherever they are at on their data science journey, the Red Hat OpenShift Data Science Platform Engagement, and the MLOps Foundation Engagement.

The Red Hat OpenShift Data Science Platform Engagement focuses on helping customers get up and running with RHODS and integrate it with their existing enterprise services.  The MLOps Foundation Engagement is designed to help customers that have trained a machine learning model and are hoping to leverage MLOps to move beyond a data science experiment, and to create a production ready ML service.

This article will focus on the MLOps Foundation Engagement, but to learn more about the Red Hat OpenShift Platform Engagement, see the companion post [here](rhods-platform-engagement.md).

## MLOps Foundation Engagement Overview

The MLOps Foundation Engagement seeks to help customers that have started experimenting with machine learning and have possibly even trained train a machine learning model, but are asking the question of "What do I do now?"

The MLOps Foundation is designed to help customers move out of the experimentation phase and create a robust, production ready machine learning service.

The engagement delivers three key capabilities to help customers to productionize their machine learning models:

* Model to Microservice: Take an existing ML model prototype and deploy it as an API service endpoint.
* CI/CD Automation: Introduce CI/CD automation to with kube-native tooling to help train and release models faster, more often, and with higher confidence.
* Observable Metrics: Create observability into model, application, and business metrics in order to enable actionable decisions and continuous improvement.

For additional information on how Red Hat delivers MLOps solutions, refer to Red Hat's [Enterprise MLOps Reference Design](https://cloud.redhat.com/blog/enterprise-mlops-reference-design).

## Engagement Approach

In the MLOps Foundation Service Offering, Red Hat will work directly with our customers Data Scientists, Application Developers/ML Engineers, and DevOps Engineers to create a solution that not only meets their specific requirements, bridging the gap between disciplines, and helping to create a repeatable solution for future MLOps efforts.  

Red Hat strives to enable our customers to deliver not just their first machine learning model, but future models as well.  By creating a 

## Engagement Sizing

The MLOps Foundation is available in a number of different sizing options and capabilities to help meet specific customer needs and requirements.

A basic Proof of Concept (PoC) may include building out a minimal machine learning pipeline for training and deploying a machine learning model.  A basic PoC most likely is only concerned with deploying to a PoC or dev environment and is not designed to introduce a production ready service.  The machine learning use case for a PoC may often include real world uses cases and data but prioritizes proving out the patterns and capabilities of the RHODS platform and OpenShift as an MLOps tool.  

A PoC style engagement will usually start at 8 weeks of time with Red Hat providing two part time resources (Project Manager and Architect) and one full time resource (Senior Consultant).

Longer term engagements may include many of the following additional capabilities:
* Deploying the model to a three tiered application environment (dev, test, and prod) with the ability to promote changes using CI/CD
* A strong testing framework throughout the model training and promotion process
* Multiple use cases/models
* Use case specific custom metrics and monitoring capabilities
* Integration with existing enterprise toolings
* Integration with existing application components
* Automated retraining capabilities

A longer term engagement generally start with a minimum 12 weeks of time with Red hat providing two part time resources (Project Manager and Architect) and one full time resource (Senior Consultant) but may go up to six months for multiple uses cases with a second full time resource.

## Pre-Reqs

Customers are required to have a functioning OpenShift cluster prior to the start of the engagement with a dynamic storage provisioning such as OpenShift Data Foundations or the VMWare CSI Driver Operator.

The MLOps Foundation is a great follow up engagement for a customer that has completed the RHODS Platform Engagement, but it is not strictly required.  If the customer has not yet installed RHODS on the target cluster, additional time may need to be scoped to configure a minimum install of RHODS.

For the most success with the MLOps Foundation, it is strongly recommended that the customer select a use case and train a machine learning model prior to the start of the engagement.  Data scientists collaborating with Red Hat may continue to iterate on the model throughout the engagement, but it is highly recommended to have a minimally viable model in order to minimize delays.

## Conclusion

If you or your business are interested in AI/ML Services offered by Red Hat, speak to your Red Hat account team, or reach out via https://www.redhat.com/en/contact?contact=sales.
