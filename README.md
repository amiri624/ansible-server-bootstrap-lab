
# ansible-server-bootstrap-lab

```bash
Control Node (Ansible)
        │
        ├── Web Server
        ├── Monitoring Server
        └── Docker Host
```
---
```bash
ansible-server-bootstrap-lab/
│
├── ansible.cfg
│
├── inventory/
│   └── hosts.ini
│
├── playbooks/
│   ├── site.yml
│   ├── docker.yml
│   ├── nginx.yml
│   ├── users.yml
│   └── security.yml
│
├── roles/
│   ├── common/
│   │   ├── tasks/
│   │   │   └── main.yml
│   │   └── handlers/
│   │       └── main.yml
│   │
│   ├── docker/
│   │   └── tasks/main.yml
│   │
│   ├── nginx/
│   │   ├── tasks/main.yml
│   │   └── templates/nginx.conf.j2
│   │
│   ├── users/
│   │   └── tasks/main.yml
│   │
│   └── security/
│       └── tasks/main.yml
│
├── files/
│   └── motd.txt
│
├── templates/
│   └── index.html.j2
│
├── scripts/
│   ├── bootstrap.sh
│   └── deploy.sh
│
├── logs/
│   └── ansible.log
│
├── backups/
│   └── README.md
│
├── .gitignore
└── README.md
```












