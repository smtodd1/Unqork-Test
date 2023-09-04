# Unqork-Test
Unqork Ansible take home
Steve Todd
Interview 09/05/23 prereq 
Instructions:

Please fork or create a new GitHub repository to work on this assignment. Upon completion, share the repo with jeremy.reed@unqork.com.
You may use any cloud provider for this task; AWS, Azure, and GCP all have free offerings. If you cannot set up a cloud environment within the timeframe, please focus on completing the code.
If you’re confident in your code, you can skip the deployment stage.
 

Task:

Write an Ansible playbook or role to deploy a new namespace in an existing Kubernetes cluster. Use Ansible’s Kubernetes modules for this task and deploy all resources within this namespace.
Create a ConfigMap and a Secret within the namespace using Ansible. The ConfigMap should hold application settings, and the Secret should hold sensitive information like API keys.
Deploy a simple stateful application such as Redis or MongoDB using a StatefulSet within the namespace. Make sure to set up persistent storage for the StatefulSet.
Implement a CI/CD pipeline using a tool of your choice (GitHub Actions, GitLab CI, Jenkins, etc.). The pipeline should automatically deploy your Kubernetes resources when code changes are pushed to your GitHub repository.
Create a simple architecture diagram outlining how the different Kubernetes resources interact with each other. Add this diagram to your GitHub repository.
 

Assumptions:

Feel free to make assumptions about existing cluster setup, networking, storage classes, or role-based access controls. Document any assumptions you make.

 

Extra Credit:

Add Horizontal Pod Autoscaling (HPA) to your stateful application based on CPU or memory usage. Configure the HPA settings using Ansible.
Implement a simple webhook server that will be triggered at the end of your CI/CD pipeline. This webhook should send a notification (e.g., to a Slack channel) about the deployment status. 
