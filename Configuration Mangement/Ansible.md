
* Ansible uses Secure Shell (SSH) to execute commands on remote machines which makes it agent-less

### Modules
* reusable , can be executed directly, remotely, or through Playbooks. 
* These modules are reusable components that can be used by Ansible API, or by Ansible or Ansible Playbook programs 
           can create custom modules
* **Ansible cloud modules** are used to automate different tasks like cloud provisioning and workloads automation. 
  Ansible supports different public clouds like Azure.
* #### Using these modules and Playbook language, you can provision and
  - [ ]     manage the lifecycle of a virtual machine (VM) in Microsoft Azure, 
  - [ ]     manage different services and 
  - [ ]     resources such as availability sets, 
  - [ ]     auto-scaling policies, 
  - [ ]     Azure Container Service, 
  - [ ]     Azure DNS, Azure Function Apps,
  - [ ]     Azure load balancers, 
  - [ ]     disks, and 
  - [ ]     network interfaces.

Terms
* Virtual network
* subnet
* 

Notes
* You could use Azure Cloud Shell (shell.azure.com) as your controller host. Ansible is pre-installed on Azure Cloud Shell. 
* If you are going to use tools such as Ansible Tower or Jenkins, you will need to use the option of declaring the service principal values as environment variables.
* For a development environment, [create a credentials file for Ansible on your host virtual machine](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/ansible-install-configure#create-azure-credentials).

Examples 
* [Create VM](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/ansible-create-vm)
* 


References
* [Ansinble on Azure](https://docs.microsoft.com/en-us/azure/ansible/)
* [Automate Azure Resources with Ansible - has more links](https://channel9.msdn.com/Shows/Azure-Friday/Automate-Azure-Resources-with-Ansible?term=Ansible&lang-en=true)
* [Azure Friday: Running Ansible on Azure](https://channel9.msdn.com/Shows/Azure-Friday/Running-Ansible-on-Azure?term=Ansible&lang-en=true)
