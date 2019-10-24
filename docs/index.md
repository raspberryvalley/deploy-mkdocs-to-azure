# Welcome

This is a continuous deployment Demo site. For a full guide, read the [full guide here](http://raspberry-valley.azurewebsites.net/Deploy-MkDocs-to-Azure/), or simply host this site locally.

## The workflow

What happens under the hood? In a nutshell, this is your workflow:

* You commit site changes to your repository (master branch)
* Webhook invokes Azure CD (copies content to Azure Web App)
* Kudu scripts runs Python, installs mkdocs, compiles the web site, deploys the web site

Easy, right? You only focus on writing code, the system deploys itself once you commit. No more admin!

## Links

* [Installation Guide](http://raspberry-valley.azurewebsites.net/Deploy-MkDocs-to-Azure/)
* [Installation Guide on this site](deploy-mkdocs.md)
* [Kudu](https://github.com/projectkudu/kudu) - the heavy lifting of deployment is done via **Kudu** scripting. Here is the home page and source
* [Custom Deployment Blog Series](http://blog.amitapple.com/post/38417491924/azurewebsitecustomdeploymentpart1/)