# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

## Virtual Machine (VM):

- Cost: VMs generally require more management and maintenance, potentially increasing operational costs. You also have to consider the cost of the VM itself.
- Scalability: VMs can be vertically or horizontally scaled but require manual intervention. Horizontal scaling might involve load balancers and more VM instances.
- Availability: You need to manage backups, high availability configurations, and potentially implement failover strategies.
- Workflow: Deployment can be more complex, involving provisioning, configuration, and ongoing maintenance tasks.

## App Service:

- Cost: App Service abstracts away infrastructure management, potentially reducing operational costs. You pay for the compute resources you use.
- Scalability: App Service provides auto-scaling out-of-the-box based on demand.
- Availability: Microsoft manages the underlying platform and ensures high availability.
- Workflow: Deployment is simpler, with built-in CI/CD integration, making it easier to deploy updates.
- 
### Choose the appropriate solution (VM or App Service) for deploying the app:
For a CMS app where rapid deployment, scalability, and cost-effectiveness are crucial, App Service would be the preferred option due to its managed nature, built-in scalability, and easier deployment workflows.

### Justify your choice:
App Service provides a managed environment that simplifies infrastructure management, reduces operational overhead, and allows for quicker deployments, making it an ideal choice for CMS applications that require agility, scalability, and cost-efficiency.

### Assess app changes that would change your decision.
the CMS app requires specific configurations, dependencies, or performance optimizations that are not supported by App Service, such as custom networking configurations, specialized software installations, or GPU-intensive tasks, then a VM might become a more suitable option.

