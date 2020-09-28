HybridSharedServices
====================

Hybrid Shared Services makes use of a traditional hub & spoke vNet design by
leveraging Shared Services in Azure and separate Prod & Non-Prod environments.
Both Prod & Non-Prod can talk to Shared Services, but Prod & Non-Prod are
completely isolated from one another.

![](media/Screenshot 2020-09-28 102255.jpg)

From on-prem there's separate access to each of the 3 routing domains.

## Deployment

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmarckean%2FHybridSharedServices%2Fmaster%2FAzureDeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmarckean%2FHybridSharedServices%2Fmaster%2FAzureDeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>