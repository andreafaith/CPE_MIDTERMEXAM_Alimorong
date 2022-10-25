/* 1. Create a repository in your GitHub account and label it CPE_MIDEXAM_SURNAME. 
2. Clone the repository and do the following: 
   2.1 Create an Ansible playbook that does the following with an input of a config.yaml file and arranged Inventory file: 
   2.2 Install and configure Elastic Stack in separate hosts (Elastic Search, Kibana, Logstash) • Install Nagios in one host 
   2.3 Install Grafana,Prometheus and Influxdb in seperate hosts (Influxdb,Grafana,Prometheus) 
   2.4 Install Lamp Stack in separate hosts (Httpd + Php,Mariadb) 
3. Document all your tasks using this document. Provide proofs of all the ansible playbooks codes and successful installations.
4. Document the push and commit from the local repository to GitHub. 
5. Finally, paste also the link of your GitHub repository in the documentation */


/* ├── ansible.cfg
├── config.yml
├── files
│   ├── andreafaith
│   ├── andreafaith-centos.conf
│   ├── andreafaith-ubuntu.conf
│   ├── elasticsearch.repo
│   ├── grafana.repo
│   ├── index.html
│   ├── influxdb.repo
│   ├── logstash.conf
│   └── prometheus.service
├── inventory
├── playbook.yml
└── roles
    ├── configcentoses
    │   └── tasks
    │       └── main.yml
    ├── configcentosgrafana
    │   └── tasks
    │       └── main.yml
    ├── configcentoshttpd
    │   └── tasks
    │       └── main.yml
    ├── configcentosinfluxdb
    │   └── tasks
    │       └── main.yml
    ├── configcentoskibana
    │   └── tasks
    │       └── main.yml
    ├── configcentosmaria
    │   └── tasks
    │       └── main.yml
    ├── configcentosprom
    │   └── tasks
    │       └── main.yml
    ├── configlogstash
    │   └── tasks
    │       └── main.yml
    ├── configubuntuapache
    │   └── tasks
    │       └── main.yml
    ├── configubuntues
    │   └── tasks
    │       └── main.yml
    ├── configubuntugrafana
    │   └── tasks
    │       └── main.yml
    ├── configubuntuinfluxdb
    │   └── tasks
    │       └── main.yml
    ├── configubuntukibana
    │   └── tasks
    │       └── main.yml
    ├── configubuntumaria
    │   └── tasks
    │       └── main.yml
    ├── configubuntunagios
    │   └── tasks
    │       └── main.yml
    ├── configubuntuprom
    │   └── tasks
    │       └── main.yml
    ├── installubuntupkg
    │   └── tasks
    │       └── main.yml
    ├── stopfirewalld
    │   └── tasks
    │       └── main.yml
    └── stopufw
        └── tasks
            └── main.yml */
