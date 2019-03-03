# nginxLaunchTemplate

[![Build Status](https://travis-ci.org/fortunecookiezen/nginxLaunchTemplate.svg?branch=master)](https://travis-ci.org/fortunecookiezen/nginxLaunchTemplate)

CloudFormation templates for a herd of nginx cattle

* templates/nginx.yaml is an EC2 template
* templates/nginxCluster.yaml implements a classic load balancer
* templates/nginxLaunchTemplate.yaml is just the Launch Template configuration. Not a lot of examples of those that I've found
* templates/nginxNLBv2Cluster.yaml is the real-deal. It's is a complete deployement for an nginx proxy asg. Still under development

## To Do

* Implement eip assumption
* Implement tls configurations
* Improve automatic configuration of nginx proxies
