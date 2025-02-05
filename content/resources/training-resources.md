SparkFabrik offers access to a set of training resources.

Some of them are _self-service_ and can be accessed by every employee as they see fit. Some others are licensed on a per-seat basis and require the creation of a personal account and relative license.

This page lists all the available resources, providing a link to them and a mean to obtain access when required.

At the bottom of this page, in the [Filing training requests](#filing-training-requests) section, we explain how to submit requests for specific training courses/resources and keep an eye on new training resources that SparkFabrik may make available to everyone.

## Training resources

Please find here a TOC of the available training resources.

| Name | Area | Topics | Access type |
|---|---|---|---|
| [Udemy](#udemy)| Development | Angular, React, React Native, Hasura | Credentials |
| [Ultimate Courses](#ultimate-courses) | Development | Angular, React, Typescript | Credentials |
| [Drupalize.me](#drupalizeme) | Development | Drupal | Credentials |
| [AWS Skill Builder](#aws-skill-builder) | Cloud | Amazon Web Services | Corporate account |
| [Google SkillBoost](#google-skillboost) | Cloud | Google Cloud Platform | Corporate account |
| [Cloud Academy](#cloud-academy) | Cloud | Vendor-specific services (AWS, GCP, Azure, Alibaba), Kubernetes, complete Cloud training offering | Reserved seats |

### Development

#### Udemy

We have a Udemy account we use to buy development courses that may be necessary to improve our skills or build them from zero.  
Mainly you can find training on frameworks and technologies (also Cloud technologies) of common use in SparkFabrik (Angular, React, AWS and others), but also on more specific tools.

Given the wide offering of topics on Udemy, more courses can be added in the future, even in non-technical topics.

> 1. Make sure you are [logged into GCloud](/guides/local-development-environment-configuration#log-into-gcloud) with your SparkFabrik account.  
> 2. Head to [Udemy](https://www.udemy.com/join/login-popup/), then obtain access credentials issuing this command into a terminal:
> 
> ```bash
> gcloud secrets versions access "latest" --secret credentials-udemy --project sf-public-ring
> ```

#### Ultimate Courses

On Ultimate Courses, you can access a set of very thorough and deep courses on Angular by Todd Motto. Those courses are very good for those who want to deepen their understanding of Angular, get the hang of its internals and learn how to use NgRx (a reactive state management library).

> 1. Make sure you are [logged into GCloud](/guides/local-development-environment-configuration#log-into-gcloud) with your SparkFabrik account.  
> 2. Head to [Ultimate Courses](https://app.ultimatecourses.com), then obtain access credentials issuing this command into a terminal:
> 
> ```bash
> gcloud secrets versions access "latest" --secret credentials-ultimate-courses --project sf-public-ring
> ```

#### Drupalize.me

On Drupalize.me you can build up a strong understanding of Drupal CMS, following extensive training paths that will guide you from the basics to the more advanced topics.

Those resources are available to PHP developers who need to understand how Drupal works as well as to Drupal developers who need to dig deeper into specific parts of the framework.

> 1. Make sure you are [logged into GCloud](/guides/local-development-environment-configuration#log-into-gcloud) with your SparkFabrik account.  
> 2. Head to [Drupalize.me](https://drupalize.me), then obtain access credentials issuing this command into a terminal:
> 
> ```bash
> gcloud secrets versions access "latest" --secret credentials-drupalize-me --project sf-public-ring
> ```

### Cloud

#### AWS Skill Builder

As AWS Partners, SparkFabrik has free access to a huge amount of training material on Amazon's Cloud offering and services, through their _Skill Builder_ portal.

Those resources are great if you and your team want to leverage AWS services in the project at hand.

> To get access, first you have to [register an AWS Partner Network account](https://partnercentral.awspartner.com/APNSelfRegister) using your `sparkfabrik.com` email and your personal information.
> Then, head to [AWS Skill Builder](https://explore.skillbuilder.aws) and access using credentials you've just entered.

#### Google SkillBoost

As GCP Partners, SparkFabrik has free access to a huge amount of training material on Google Cloud Platform's offerings and services, through their _Skill Boost_ portal.

Those resources are great if you and your team want to leverage GCP services in the project at hand.

> Head to [GCP Skill Boost](https://partners.cloudskillsboost.google), then access using your `sparkfabrik.com` account.

With Google SkillBoost comes **Qwiklabs**, a service providing real cloud environments that help developers and IT professionals learn cloud platforms and software, such as Firebase, Kubernetes and more.

> To access **QwikLabs** you just have to fill in [a registration form](https://partner.cloudskillsboost.google/course_sessions/1257385/video/187468
) using your `sparkfabrik.com' account.


#### Cloud Academy

Cloud Academy offers a complete environment to train for many Certifications Exams, from vendor-specific ones to CNCF certifications programs like KCA/CKAD.

The platform offers video courses, training sandboxes, guided labs and exam simulations.

There is no self-service access to Cloud Academy platform: SparkFabrik has a specific number of seats that can be assigned depending on the Certified Training Program we put in place twice a year.

If you want to discuss a Certified Training on Cloud topics, please let us know by filing a request as described below.

> Head to [Cloud Academy](https://cloudacademy.com/), then access using your `sparkfabrik.com` account. **You need to have a valid, active seat to access the training material**.

## Filing training requests

SparkFabrik employees can file a request for specific training resources, by filling in [this _Training Request_ form](https://forms.gle/D3sMame93iJ6avxX7).

The requests will be evaluated by the management taking into account many factors, among which:

* The available training budget
* The relevance and impact on your professional position/growth
* The alignment with corporate strategy
* Your training track record (if any)

To speed up the evaluation process, please make sure to provide detailed information, following each field's suggestion.
