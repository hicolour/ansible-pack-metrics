# ansible-pack-metrics


Ansible playbook for well proven metrics collectors stack

* Graphite
* Statsd
* Grafana (>= 2.0.2)


Tested on Ubuntu 14.04 LTS

```
ansible-playbook -v -i ansible_hosts playbook.yml -e target=192.168.11.92 --sudo -K
```
