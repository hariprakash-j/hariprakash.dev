+++
author = "Hari Prakash"
title = "Using make and rain to build and deploy cfn templates"
date = "2023-08-07"
description = "Building and deploying cloudformation templates with make and rain a cfn devops tool by aws"
tags = [
    "aws",
    "IaaS",
]
+++

AWS CDK a great framework to make and deploy large and small and complex and simple applications. However I feel like its sometimes a bit too much for small deployments like say a lambda with some role and a event rule for some simple automation. I have been using and contributing to an AWS Cloudformation devops tool called rain and its great for working with cfn stacks and stacksets. Lets try to make a lambda that runs some python code and deploy it using rain!

Here is a some basic python code that is intended to work with lambda

...code…

Its a little basic, just some code that will return hello world as a JSON when run. Now, lets make a simple cfn template to deploy this function. I am going to use the SAM transform here, its quite handy when writing a cfn template for a lambda as its much more concise and easier to use https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-resource-function.html.

More to follow...
