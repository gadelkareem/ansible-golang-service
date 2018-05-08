# Ansible Golang Service
Ansible role for deploying and running a Golang binary as a systemd service

- Copy the files into your playbook and set the service_name and base_path to your application.
- The service uses rsyslog to create error.log and access.log.
- Logrotate config included.
- Handles [Beego framework](https://beego.me/) logging.
