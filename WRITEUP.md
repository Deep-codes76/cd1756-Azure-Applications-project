### Analyze, choose, and justify the appropriate resource option for deploying the app

For deploying the CMS application on Azure, two options were considered: Virtual Machine (VM) and Azure App Service.

A Virtual Machine gives full control over the server. We can install any software, configure the system manually, and manage the environment ourselves. However, this also means we must handle updates, security, scaling, and monitoring manually. VMs usually cost more and require more maintenance.

Azure App Service is a Platform as a Service (PaaS) that is designed for hosting web applications. It handles server management, updates, and scaling automatically. Deployment is also easier because it can be connected directly to a GitHub repository. For this project, the free F1 pricing tier also makes it cost-effective.

For the CMS project, Azure App Service was chosen because it is simpler to deploy, requires less maintenance, and provides built-in scalability and availability for a Flask web application.

### Assess app changes that would change your decision

If the application required custom system configurations, special software, or more control over the operating system, a Virtual Machine would be a better choice. A VM would allow installing additional services and configuring the server environment more freely.

For this CMS application, those requirements are not needed, so App Service remains the better and simpler option.
