This Ansible playbook helps with joining Red Hat CloudForms Appliances to a Microsoft Active Directory Domain,
as a pre-requisite to setting up authentication for said AD domain.

Ensure you have an inventory of worker/ UI appliance to run this upon.
Before running the playbook ensure `var.yml` is updated with your own variablescas below:

 1: Active Directory Domain name

 2: Active Directory Domain User (ensure the domain user has permission domain admin permission)

 3: Domain User password

 4: optionally, Domain controller IP if no DNS configured in the environment 
