# nginxLaunchTemplate

[![Build Status](https://travis-ci.org/fortunecookiezen/nginxLaunchTemplate.svg?branch=master)](https://travis-ci.org/fortunecookiezen/nginxLaunchTemplate)

CloudFormation templates for a herd of nginx cattle

* templates/nginx.yaml is an EC2 template
* templates/nginxCluster.yaml implements a classic load balancer
* templates/nginxLaunchTemplate.yaml is just the Launch Template configuration. Not a lot of examples of those that I've found probably outdated now.
* templates/nginxNLBv2Cluster.yaml is the real-deal. It's is a complete deployement of an network load-balancer nginx proxy asg.
* templates/nginxAlbv2ReverseProxyCluster.yaml is the same thing at Layer 7. tested.

## To Do

* fix security groups on templates/nginxAlbCluster.yaml to restrict acces better
* update templates/nginxLaunchTemplate.yaml to be a better example of things
