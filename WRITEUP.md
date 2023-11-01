*Analyze costs, scalability, availability, and workflow
- Analyze Costs:
      Azure App Service is often cheaper for web app because you don't need to care more about infrastructure but it also has limitation on infrastructure when you will be hard to customize hardware.
- Scalability: 
      Both of them provide ability to autoscale, scaling on app service is more simple and quick than virtual machine, because has available instances, to VM we need to adjust it manually. 
- Availability: 
      Azure App Service provides built-in load balancing and redundancy for high availability without manual configuration, while Azure Virtual Machines allow you to implement availability sets or zones for fault tolerance and data center resilience, requiring more setup and management effort.
- Flow:
      Deploying an application on app service is simpler than VM. App service has available enviroment for specific language and we just give it code.

*Choose the appropriate solution (VM or App Service) for deploying the app*
      Currently, Article CMS is still at begining stage with some simple features like create, edit post so I choose App Service for fast and simple deploying.

*Assess app changes that would change your decision.
      In the future, If the app become really large and more users I will think about VM for better performance but the app service is too enough for current system
