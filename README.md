# Project-LB

🌐 AWS EC2 Role:

- Automated EC2 instance launch with dynamic creation of key pairs and security groups.

- Dynamically updated the inventory and /etc/ansible/hosts file with essential connection details, such as the Ansible user, private key file, and connection type.

🌐 Web Role:

- Configured Apache servers on the launched EC2 instances.

- Transferred a comprehensive index.html file from the local system to the instances, featuring HTML, CSS, and even Jinja2 code.

- Started and ensured the smooth running of Apache services.

🌐 Load Balancer Role:

- Set up a Load Balancer system by installing and configuring HAProxy.

- Utilized Jinja2 templating in the configuration file to dynamically capture IPs of the updated instances from the inventory.

- Initiated the HAProxy service, creating a robust traffic controller for efficient scaling out and scaling in.

🌐 Result:

- The environment now boasts a robust and automated infrastructure, capable of handling scaling challenges effortlessly.

- Demonstration of the traffic control service is evident by accessing the web pages through the HAProxy IP, showcasing the dynamic routing of traffic to newly updated instances.
