This is a project to automatically setup logstash on nutanix cluster
and start sending logs to an ES endpoint.

Please export ES_PATH variable to point to ES endpoint before running playbook

Update hosts file to add a new AOS. 

Update playbook to point to newly added host.

Run> ansible-playbook playbook.yml -i hosts

Contact: vinod@nutanix.com

