# test-naw

https://www.google.com/url?sa=i&url=https%3A%2F%2Fgithub.com%2Flogos&psig=AOvVaw3fcwm8KDYjBEpPFwKocCJD&ust=1611205622758000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCNDu4-jeqe4CFQAAAAAdAAAAABAD


[[_TOC_]]

In this guildeline you will build and run self-hosted Docker agents on Azure Container Instances. It is a simple and economic way of running Azure DevOps agents in the cloud. This workflow removes the obstacle of hosting your own server or virtual machine to run self-hosted agents.

You will find base images in the repo [de-ado-agent-blueprints](https://volvocargroup1.visualstudio.com/Volvo%20Cars%20Inner%20Source/_git/de-ado-agent-blueprints). Use those images as a starting point for your own agents by cloning that repo.

Using Docker Desktop and ACR, you can customize the images to your requirements and test the agents in an agent pool in your Azure DevOps project. Once tested, push the image to your repository (ACR) and spin up the agent in an Azure Container Instance.
## Workflow
![image.png](/.attachments/image-dd38bc61-330d-4dc6-9b15-4e1632037964.png)
