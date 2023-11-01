# GitOps as Landing zone enhancement

This project demonstrates a powerful concept of cooperation between 
* GitHub organization
* Terraform Enterprise Workspaces and Sentinel check
* Azure Cloud as provisioning target

The concept is geared towards keeping all your project as code in GitHub. Apart from your proper source code this incompasses
* the infrastructure as [TFE Config](https://www.terraform.io/cloud-docs/vcs/github-enterprise)
* the DevOps workflow as [GH Actions](https://docs.github.com/en/actions)
* the security governance as [Sentinels](https://www.terraform.io/cloud-docs/sentinel/manage-policies)
* the [bootstraping](https://github.com/lzf-azure/bootstrap) as Pyton executable

# What will I get from this

In essence a basic workflow, to get the gist, and expand for your corporate requirements:

![image](https://user-images.githubusercontent.com/7328002/184539590-f50b4ea5-8776-4456-8fb7-c15bd5fce5f0.png)

# How do I start
Checkout and run the [bootstrap repo](https://github.com/lzf-azure/bootstrap)

# More details
For more details on the background of this soulution, check out my blog at https://www.csabameszaros.com/2023/08/05/azure-devops-landing-zone/
