# Ansible-Mattermost-RocketChat
This structure was the backbone of my entire setup. It helped me to to managing a complex infrastructure and multiple services.

I used directories organized by the services they represent (Jenkins, JMeter, Mattermost, Rocketchat, Zabbix). Each service directory contains specific configurations and roles tailored to that service. These modules simplified maintenance and allowed me to work on each service independently.

It was also role based configuration that iin each service directory, there were roles and tasks defined. For example, the Mattermost directory includes roles for Mattermost, Nginx, PostgreSQL, and Zabbix Agent, each with their respective files and tasks.
