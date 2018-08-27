---
name: AWS Auto Scaling
x-slug: aws-auto-scaling
description: Auto Scaling helps you maintain application availability and allows you
  to scale yourAmazon EC2capacity up or down automatically according to conditions
  you define. You can use Auto Scaling to help ensure that you are running your desired
  number of Amazon EC2 instances. Auto Scaling can also automatically increase the
  number of Amazon EC2 instances during demand spikes to maintain performance and
  decrease capacity during lulls to reduce costs. Auto Scaling is well suited both
  to applications that have stable demand patterns or that experience hourly, daily,
  or weekly variability in usage.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Autmobile
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Auto Scaling API - Attach Instances
  x-api-slug: actionattachinstances-get
  description: Attaches one or more EC2 instances to the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionattachinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionattachinstances-get-openapi.md
- name: AWS Auto Scaling API - Attach Load Balancers
  x-api-slug: actionattachloadbalancers-get
  description: Attaches one or more Classic load balancers to the specified Auto Scaling
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionattachloadbalancers-get-openapi.md
- name: AWS Auto Scaling API - Attach Load Balancer Target Groups
  x-api-slug: actionattachloadbalancertargetgroups-get
  description: Attaches one or more target groups to the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionattachloadbalancertargetgroups-get-openapi.md
- name: AWS Auto Scaling API - Create Auto Scaling Group
  x-api-slug: actioncreateautoscalinggroup-get
  description: Creates an Auto Scaling group with the specified name and attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actioncreateautoscalinggroup-get-openapi.md
- name: AWS Auto Scaling API - Create Or Update Tags
  x-api-slug: actioncreateorupdatetags-get
  description: Creates or updates tags for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actioncreateorupdatetags-get-openapi.md
- name: AWS Auto Scaling API - Delete Auto Scaling Group
  x-api-slug: actiondeleteautoscalinggroup-get
  description: Deletes the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondeleteautoscalinggroup-get-openapi.md
- name: AWS Auto Scaling API - Delete Policy
  x-api-slug: actiondeletepolicy-get
  description: Deletes the specified Auto Scaling policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondeletepolicy-get-openapi.md
- name: AWS Auto Scaling API - Describe Account Limits
  x-api-slug: actiondescribeaccountlimits-get
  description: Describes the current Auto Scaling resource limits for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeaccountlimits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeaccountlimits-get-openapi.md
- name: AWS Auto Scaling API - Describe Auto Scaling Groups
  x-api-slug: actiondescribeautoscalinggroups-get
  description: Describes one or more Auto Scaling groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeautoscalinggroups-get-openapi.md
- name: AWS Auto Scaling API - Describe Auto Scaling Instances
  x-api-slug: actiondescribeautoscalinginstances-get
  description: Describes one or more Auto Scaling instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeautoscalinginstances-get-openapi.md
- name: AWS Auto Scaling API - Describe Auto Scaling Notification Types
  x-api-slug: actiondescribeautoscalingnotificationtypes-get
  description: Describes the notification types that are supported by Auto Scaling.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeautoscalingnotificationtypes-get-openapi.md
- name: AWS Auto Scaling API - Describe Lifecycle Hooks
  x-api-slug: actiondescribelifecyclehooks-get
  description: Describes the lifecycle hooks for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribelifecyclehooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribelifecyclehooks-get-openapi.md
- name: AWS Auto Scaling API - Describe Load Balancers
  x-api-slug: actiondescribeloadbalancers-get
  description: Describes the load balancers for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeloadbalancers-get-openapi.md
- name: AWS Auto Scaling API - Describe Load Balancer Target Groups
  x-api-slug: actiondescribeloadbalancertargetgroups-get
  description: Describes the target groups for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeloadbalancertargetgroups-get-openapi.md
- name: AWS Auto Scaling API - Describe Metric Collection Types
  x-api-slug: actiondescribemetriccollectiontypes-get
  description: Describes the available CloudWatch metrics for Auto Scaling.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribemetriccollectiontypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribemetriccollectiontypes-get-openapi.md
- name: AWS Auto Scaling API - Describe Notification Configurations
  x-api-slug: actiondescribenotificationconfigurations-get
  description: Describes the notification actions associated with the specified Auto
    Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribenotificationconfigurations-get-openapi.md
- name: AWS Auto Scaling API - Describe Policies
  x-api-slug: actiondescribepolicies-get
  description: Describes the policies for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribepolicies-get-openapi.md
- name: AWS Auto Scaling API - Describe Scaling Activities
  x-api-slug: actiondescribescalingactivities-get
  description: Describes one or more scaling activities for the specified Auto Scaling
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribescalingactivities-get-openapi.md
- name: AWS Auto Scaling API - Describe Scheduled Actions
  x-api-slug: actiondescribescheduledactions-get
  description: Describes the actions scheduled for your Auto Scaling group that haven't
    run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribescheduledactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribescheduledactions-get-openapi.md
- name: AWS Auto Scaling API - Describe Termination Policy Types
  x-api-slug: actiondescribeterminationpolicytypes-get
  description: Describes the termination policies supported by Auto Scaling.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeterminationpolicytypes-get-openapi.md
- name: AWS Auto Scaling API - Detach Instances
  x-api-slug: actiondetachinstances-get
  description: Removes one or more instances from the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondetachinstances-get-openapi.md
- name: AWS Auto Scaling API - Detach Load Balancers
  x-api-slug: actiondetachloadbalancers-get
  description: Detaches one or more Classic load balancers from the specified Auto
    Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondetachloadbalancers-get-openapi.md
- name: AWS Auto Scaling API - Detach Load Balancer Target Groups
  x-api-slug: actiondetachloadbalancertargetgroups-get
  description: Detaches one or more target groups from the specified Auto Scaling
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondetachloadbalancertargetgroups-get-openapi.md
- name: AWS Auto Scaling API - Disable Metrics Collection
  x-api-slug: actiondisablemetricscollection-get
  description: Disables group metrics for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondisablemetricscollection-get-openapi.md
- name: AWS Auto Scaling API - Enable Metrics Collection
  x-api-slug: actionenablemetricscollection-get
  description: Enables group metrics for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionenablemetricscollection-get-openapi.md
- name: AWS Auto Scaling API - Put Lifecycle Hook
  x-api-slug: actionputlifecyclehook-get
  description: Creates or updates a lifecycle hook for the specified Auto Scaling
    Group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputlifecyclehook-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputlifecyclehook-get-openapi.md
- name: AWS Auto Scaling API - Put Notification Configuration
  x-api-slug: actionputnotificationconfiguration-get
  description: Configures an Auto Scaling group to send notifications when specified
    events take place.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputnotificationconfiguration-get-openapi.md
- name: AWS Auto Scaling API - Put Scaling Policy
  x-api-slug: actionputscalingpolicy-get
  description: Creates or updates a policy for an Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputscalingpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputscalingpolicy-get-openapi.md
- name: AWS Auto Scaling API - Put Scheduled Update Group Action
  x-api-slug: actionputscheduledupdategroupaction-get
  description: Creates or updates a scheduled scaling action for an Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputscheduledupdategroupaction-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputscheduledupdategroupaction-get-openapi.md
- name: AWS Auto Scaling API - Resume Processes
  x-api-slug: actionresumeprocesses-get
  description: Resumes the specified suspended Auto Scaling processes, or all suspended
    process, for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionresumeprocesses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionresumeprocesses-get-openapi.md
- name: AWS Auto Scaling API - Set Desired Capacity
  x-api-slug: actionsetdesiredcapacity-get
  description: Sets the size of the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionsetdesiredcapacity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionsetdesiredcapacity-get-openapi.md
- name: AWS Auto Scaling API - Suspend Processes
  x-api-slug: actionsuspendprocesses-get
  description: Suspends the specified Auto Scaling processes, or all processes, for
    the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionsuspendprocesses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionsuspendprocesses-get-openapi.md
- name: AWS Auto Scaling API - Terminate Instance In Auto Scaling Group
  x-api-slug: actionterminateinstanceinautoscalinggroup-get
  description: Terminates the specified instance and optionally adjusts the desired
    group size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionterminateinstanceinautoscalinggroup-get-openapi.md
- name: AWS Auto Scaling API - Update Auto Scaling Group
  x-api-slug: actionupdateautoscalinggroup-get
  description: Updates the configuration for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionupdateautoscalinggroup-get-openapi.md
- name: AWS Auto Scaling API - Attach Instances
  x-api-slug: actionattachinstances-get
  description: Attaches one or more EC2 instances to the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionattachinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionattachinstances-get-openapi.md
- name: AWS Auto Scaling API - Attach Load Balancers
  x-api-slug: actionattachloadbalancers-get
  description: Attaches one or more Classic load balancers to the specified Auto Scaling
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionattachloadbalancers-get-openapi.md
- name: AWS Auto Scaling API - Attach Load Balancer Target Groups
  x-api-slug: actionattachloadbalancertargetgroups-get
  description: Attaches one or more target groups to the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionattachloadbalancertargetgroups-get-openapi.md
- name: AWS Auto Scaling API - Create Auto Scaling Group
  x-api-slug: actioncreateautoscalinggroup-get
  description: Creates an Auto Scaling group with the specified name and attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actioncreateautoscalinggroup-get-openapi.md
- name: AWS Auto Scaling API - Create Or Update Tags
  x-api-slug: actioncreateorupdatetags-get
  description: Creates or updates tags for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actioncreateorupdatetags-get-openapi.md
- name: AWS Auto Scaling API - Delete Auto Scaling Group
  x-api-slug: actiondeleteautoscalinggroup-get
  description: Deletes the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondeleteautoscalinggroup-get-openapi.md
- name: AWS Auto Scaling API - Delete Policy
  x-api-slug: actiondeletepolicy-get
  description: Deletes the specified Auto Scaling policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondeletepolicy-get-openapi.md
- name: AWS Auto Scaling API - Describe Account Limits
  x-api-slug: actiondescribeaccountlimits-get
  description: Describes the current Auto Scaling resource limits for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeaccountlimits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeaccountlimits-get-openapi.md
- name: AWS Auto Scaling API - Describe Auto Scaling Groups
  x-api-slug: actiondescribeautoscalinggroups-get
  description: Describes one or more Auto Scaling groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeautoscalinggroups-get-openapi.md
- name: AWS Auto Scaling API - Describe Auto Scaling Instances
  x-api-slug: actiondescribeautoscalinginstances-get
  description: Describes one or more Auto Scaling instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeautoscalinginstances-get-openapi.md
- name: AWS Auto Scaling API - Describe Auto Scaling Notification Types
  x-api-slug: actiondescribeautoscalingnotificationtypes-get
  description: Describes the notification types that are supported by Auto Scaling.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeautoscalingnotificationtypes-get-openapi.md
- name: AWS Auto Scaling API - Describe Lifecycle Hooks
  x-api-slug: actiondescribelifecyclehooks-get
  description: Describes the lifecycle hooks for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribelifecyclehooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribelifecyclehooks-get-openapi.md
- name: AWS Auto Scaling API - Describe Load Balancers
  x-api-slug: actiondescribeloadbalancers-get
  description: Describes the load balancers for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeloadbalancers-get-openapi.md
- name: AWS Auto Scaling API - Describe Load Balancer Target Groups
  x-api-slug: actiondescribeloadbalancertargetgroups-get
  description: Describes the target groups for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeloadbalancertargetgroups-get-openapi.md
- name: AWS Auto Scaling API - Describe Metric Collection Types
  x-api-slug: actiondescribemetriccollectiontypes-get
  description: Describes the available CloudWatch metrics for Auto Scaling.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribemetriccollectiontypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribemetriccollectiontypes-get-openapi.md
- name: AWS Auto Scaling API - Describe Notification Configurations
  x-api-slug: actiondescribenotificationconfigurations-get
  description: Describes the notification actions associated with the specified Auto
    Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribenotificationconfigurations-get-openapi.md
- name: AWS Auto Scaling API - Describe Policies
  x-api-slug: actiondescribepolicies-get
  description: Describes the policies for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribepolicies-get-openapi.md
- name: AWS Auto Scaling API - Describe Scaling Activities
  x-api-slug: actiondescribescalingactivities-get
  description: Describes one or more scaling activities for the specified Auto Scaling
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribescalingactivities-get-openapi.md
- name: AWS Auto Scaling API - Describe Scheduled Actions
  x-api-slug: actiondescribescheduledactions-get
  description: Describes the actions scheduled for your Auto Scaling group that haven't
    run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribescheduledactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribescheduledactions-get-openapi.md
- name: AWS Auto Scaling API - Describe Termination Policy Types
  x-api-slug: actiondescribeterminationpolicytypes-get
  description: Describes the termination policies supported by Auto Scaling.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondescribeterminationpolicytypes-get-openapi.md
- name: AWS Auto Scaling API - Detach Instances
  x-api-slug: actiondetachinstances-get
  description: Removes one or more instances from the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondetachinstances-get-openapi.md
- name: AWS Auto Scaling API - Detach Load Balancers
  x-api-slug: actiondetachloadbalancers-get
  description: Detaches one or more Classic load balancers from the specified Auto
    Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondetachloadbalancers-get-openapi.md
- name: AWS Auto Scaling API - Detach Load Balancer Target Groups
  x-api-slug: actiondetachloadbalancertargetgroups-get
  description: Detaches one or more target groups from the specified Auto Scaling
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondetachloadbalancertargetgroups-get-openapi.md
- name: AWS Auto Scaling API - Disable Metrics Collection
  x-api-slug: actiondisablemetricscollection-get
  description: Disables group metrics for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actiondisablemetricscollection-get-openapi.md
- name: AWS Auto Scaling API - Enable Metrics Collection
  x-api-slug: actionenablemetricscollection-get
  description: Enables group metrics for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionenablemetricscollection-get-openapi.md
- name: AWS Auto Scaling API - Put Lifecycle Hook
  x-api-slug: actionputlifecyclehook-get
  description: Creates or updates a lifecycle hook for the specified Auto Scaling
    Group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputlifecyclehook-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputlifecyclehook-get-openapi.md
- name: AWS Auto Scaling API - Put Notification Configuration
  x-api-slug: actionputnotificationconfiguration-get
  description: Configures an Auto Scaling group to send notifications when specified
    events take place.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputnotificationconfiguration-get-openapi.md
- name: AWS Auto Scaling API - Put Scaling Policy
  x-api-slug: actionputscalingpolicy-get
  description: Creates or updates a policy for an Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputscalingpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputscalingpolicy-get-openapi.md
- name: AWS Auto Scaling API - Put Scheduled Update Group Action
  x-api-slug: actionputscheduledupdategroupaction-get
  description: Creates or updates a scheduled scaling action for an Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputscheduledupdategroupaction-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionputscheduledupdategroupaction-get-openapi.md
- name: AWS Auto Scaling API - Resume Processes
  x-api-slug: actionresumeprocesses-get
  description: Resumes the specified suspended Auto Scaling processes, or all suspended
    process, for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionresumeprocesses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionresumeprocesses-get-openapi.md
- name: AWS Auto Scaling API - Set Desired Capacity
  x-api-slug: actionsetdesiredcapacity-get
  description: Sets the size of the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionsetdesiredcapacity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionsetdesiredcapacity-get-openapi.md
- name: AWS Auto Scaling API - Suspend Processes
  x-api-slug: actionsuspendprocesses-get
  description: Suspends the specified Auto Scaling processes, or all processes, for
    the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionsuspendprocesses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionsuspendprocesses-get-openapi.md
- name: AWS Auto Scaling API - Terminate Instance In Auto Scaling Group
  x-api-slug: actionterminateinstanceinautoscalinggroup-get
  description: Terminates the specified instance and optionally adjusts the desired
    group size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionterminateinstanceinautoscalinggroup-get-openapi.md
- name: AWS Auto Scaling API - Update Auto Scaling Group
  x-api-slug: actionupdateautoscalinggroup-get
  description: Updates the configuration for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/autmobile/master/_listings/aws-auto-scaling/actionupdateautoscalinggroup-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.appstream.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.auto.scaling.stack.network
- type: x-articles
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=100
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=86
- type: x-code
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=85
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/autoscaling/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/AutoScaling/latest/APIReference/
- type: x-forum
  url: http://developer.amazonwebservices.com/connect/forum.jspa?forumID=30
- type: x-getting-started
  url: https://aws.amazon.com/autoscaling/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/autoscaling/pricing/
- type: x-service-health
  url: http://status.aws.amazon.com/
- type: x-website
  url: https://aws.amazon.com/autoscaling/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---